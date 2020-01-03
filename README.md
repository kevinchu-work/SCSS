# SCSS Partition
##### Common SCSS contexts for HTML5 project

------------

**WARNING: THIS PROJECT STILL UNDER DEVELOPMENT! CONSIDER CAREFULLY BEFORE USE IT ON PRODUCTION ENVIRONMENT!**

------------

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

This project is basically a re-group of common SCSS materials and following [7-1 component structure pattern](https://sass-guidelin.es/#architecture "7-1 component structure pattern"). 

However, in order to avoid duplication SCSS import without using third-party library, changes below maybe violated 7-1 pattern:
- _main.scss (renamed from main.scss) at root folder is arm to include the most (must have) basic styles, classes, variable, import of mixins, functions, placeholders...etc which is the minium set of styles and needs for all pages. Moreover, order of import has been adjusted (components before layout)
- Folder 'Pages' is arm to store files for individual webpage and/or import _main.scss
- mixins & functions has been breakdown into individual files for easiler to maintain
- _shame.scss is arm for quick fixes, hacks and questionable techniques. Ref: [shame.css](https://csswizardry.com/2013/04/shame-css/ "shame.css")
