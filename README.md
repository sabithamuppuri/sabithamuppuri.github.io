# sabithamuppuri.github.io

Personal site powered by **GitHub Pages + Jekyll**.

## Deploy
1) Create a public repo named `<username>.github.io` (replace with your username).
2) Upload these files to the repo.
3) In the repo: Settings → Pages → Source: Deploy from a branch → Branch: `main`.

## Local preview (optional)
```bash
gem install bundler jekyll
bundle init
echo 'gem "github-pages"' >> Gemfile
bundle install
bundle exec jekyll serve
```
Site will run at http://127.0.0.1:4000
