# writeit.poplus.org

The promotional site for the Poplus component, WriteIt. Compiled using Jekyll and hosted by Github at http://writeit.poplus.org

## Local development

The templates in `_layouts` and the majority of the styles in `assets/sass/` should be kept in sync with other poplus.org projects like https://github.com/mysociety/popit.poplus.org and https://github.com/mysociety/mapit.poplus.org

Styling changes specific to the WriteIt site should be made in `assets/sass/_writeit-styles.scss`.

Compile the Sass files using [(docs)](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#using_sass):

```shell
sass --watch assets/sass:css
```

## Deploying changes

The site is hosted via Github Pages. To ‘deploy’ your changes from the `master` branch, merge them into the `gh-pages` branch:

```shell
git checkout gh-pages
git merge master
git push origin gh-pages
```

Your changes will then be visible at http://mysociety.github.io/writeit.poplus.org and, once we’ve sorted out DNS, http://writeit.poplus.org too.
