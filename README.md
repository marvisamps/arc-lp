# Just a simple Landing Page

## Preview

![Landing Page Mobile Version Preview](http://i64.tinypic.com/2m4c8r6.png)
![Landing Page Desktop Version Preview](http://i65.tinypic.com/u1xzp.png)


## Download and Installation

To begin using this landing follow these steps to get started:
* Clone the repo
* npm i
* gulp dev


### Usage

After cloning, run `npm install` and then run `gulp dev`, which will open the landing page in your default browser. Watch for changes to core files, and it will live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included in the dev environment.


#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp scripts` minifies the JS files
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You MUST have npm and Gulp installed globally on your machine in order to use these features.


## About

- Resources used:
- Boostrap v4
- Font Awesome
- HTML5
- Sass
- Javascript