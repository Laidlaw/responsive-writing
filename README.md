## Responsive Writing

#### Installation
Gulp-gh-pages can be delecate.
before running `npm install && bower install`
do this:

```
git checkout --orphan gh-pages
git rm -rf .
touch README.md
git add README.md
git commit -m "Init gh-pages"
git push --set-upstream origin gh-pages
git checkout master
```
