# alexz005.github.io
personal page using [Jekyll-notes](https://github.com/AlexZ005/jekyll-notes) theme.

## Commands to update theme

git add *
git stash save #save changes to _chapters
git remote add theme git@github.com:AlexZ005/jekyll-notes
git fetch theme
#if local changes were made
#git checkout HEAD assets/css/main.scss
#git diff assets/css/main.scss
git merge --no-commit --no-ff theme/master
rm -rf _chapters/
git checkout HEAD _chapters/
git checkout HEAD _config.yml
git checkout HEAD index.md
git stash pop
