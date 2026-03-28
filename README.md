# NYC Pollen Tracker
`index.md` in this repo contains the markdown source for [nycpollentracker.com](nycpollentracker.com). 

## rendering locally
You will need to install jekyll - https://jekyllrb.com/docs/installation/.

`Gemfile` mirrors the way Github renders the site using Jekyll. After cloning this repo, run
```zsh
bundle install
```
To serve the site locally (e.g. in order to test changes before pushing to main), run
```zsh
bundle exec jekyll serve
```
and navigate to http://localhost:4000 in your browser. 