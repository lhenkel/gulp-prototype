
## Simple Setup to Automate HTML and SaSS changes using GULP4 and BrowserSync

I learned how to use gulp to watch files and browsersync, but apparently gulp
updated and most of the tutorials no longer work.  I borrowed most of this 
from https://github.com/amylily1011/gulp4-sass-bootstrap

## To Run the Project
After you clone this project you may try to install all dependencies using 

```
$ npm install
```

Before you start the server, you need to install gulp 4 globally.

```
$ npm install gulp -g
```

Then run the command below.

```
$ gulp watch
```

If you want to try running testing the browser without installing gulp globally. 
Try running the command below.

```
$ node_modules/gulp/bin/gulp.js watch
```

Browsersync should automatically open a browser on port 3000.

