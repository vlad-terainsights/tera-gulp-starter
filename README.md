# tera-gulp-starter
A gulpfile and folder to jumpstart an es5 typescript/less setup without a lot of bells and whistles

## How it works
The `gulpfile.js` just links up to the `gulp` folder. The `gulp` folder holds a `config.json` and a `tasks` directory. The `config.json` holds the paths for all of the input and outputs of the application (typescript, less, libs, etc.) The `libs.js` file specifically bundles up each respective type of asset (js, css, fonts, images) and puts them into the output folder.

## What you need to do 
Navigate to `gulp/tasks/config.json` and put in all of your paths, i.e where each aspect of the application should go. 