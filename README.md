# SASS

First initialize the project using: `npm init -y` 

`-y` parameter accepts all default values

this will create the file [package.json](package.json)


SASS is a programming language, it allows to code in ruby and compile in CSS

SASS is a node dependency, install doing the following: `npm install --save-dev node-sass`

**IMPORTANT: DON'T FORGET TO CREATE A .gitignore with `node_modules`**

## main.scss

Create a file [main.scss](./sass/main.scss).

In the [package.json](package.json) file, add the following line in the `scripts` block: `"compile-sass": "node-sass ./sass/main.scss ./css/style.css -w"`

the `-w` allows to constantly read and compile any updates that occurred.

To test that all is working, create a simple CSS block in the [main.scss](./sass/main.scss) file, then run the following command in your terminal: `npm run compile-sass`
