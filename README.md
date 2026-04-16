git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tayzaraungwlt-ux/UV-lamp.git
git push -u origin main
runs:
  using: 'node24'
  pre: 'setup.js'
  main: 'index.js'
  post: 'cleanup.js'
