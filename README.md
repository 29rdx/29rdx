git clone https://github.com/29rdx/29rdx.git && cd 29rdx   # if the repo doesn't exist: gh repo create 29rdx --public --clone && cd 29rdx

curl -fL "https://gh.crafter.run/29rdx?theme=dark"  -o dark_mode.svg
curl -fL "https://gh.crafter.run/29rdx?theme=light" -o light_mode.svg

# Optional: open both in a browser and check them before committing
# (xdg-open on Linux, open on macOS)
xdg-open dark_mode.svg light_mode.svg

# Prepend the card, keep the existing README content
cat > card.tmp <<'EOF'
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark_mode.svg" />
  <source media="(prefers-color-scheme: light)" srcset="light_mode.svg" />
  <img alt="29rdx's GitHub profile" src="dark_mode.svg" />
</picture>

EOF
cat card.tmp README.md > README.new 2>/dev/null || cp card.tmp README.new
mv README.new README.md && rm card.tmp

git add dark_mode.svg light_mode.svg README.md
git commit -m "feat: add gh-ascii profile card"
git push
