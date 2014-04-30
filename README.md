# writeit.poplus.org

The Jekyll promotional site for http://writeit.poplus.org

## Local development

The templates in `_layouts` and the majority of the styles in `assets/sass/` should be kept in sync with other poplus.org projects like https://github.com/mysociety/popit.poplus.org and https://github.com/mysociety/mapit.poplus.org

Styling changes specific to the writeit site should be made in `assets/sass/_writeit-styles.scss`.

Compile the sass files using [(docs)](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#using_sass):

```shell
sass --watch assets/sass:css
```
