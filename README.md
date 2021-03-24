# resume
Its my Resume. It uses https://github.com/hacksalot/HackMyResume

# Steps to build
```
hackmyresume BUILD resume.json TO out/resume.all -t node_modules/jsonresume-theme-caffeine/
```

* Install wkhtmltopdf for pdf.
* PDF will not have proper images since local file access is disabled. So manually generate the pdf.

```
wkhtmltopdf --enable-local-file-access out/resume.pdf.html  resume1.pdf
```


# Some themes that i like

* jsonresume-theme-eloquent
* jsonresume-theme-caffeine
* jsonresume-theme-material
* jsonresume-theme-kendall

Installing a theme
Search for the theme in http://node-modules.com/search?q=jsonresume-theme-*

```
npm install jsonresume-theme-kendall
```
