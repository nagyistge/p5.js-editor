## p5.js Editor: a Mac code editor designed for p5.js

The p5.js Editor is a simple coding environment designed for new programmers to get started with p5.js. It's modelled off of the Processing editor, and intended to provide a similar experience.

### Features
* Text editor with syntax highlighting that supports javascript, p5.js syntax, html and css.
* Creates and manages p5.js project folders
* Automatically updates new releases of p5.js and add-on libraries
* Runs sketches inside the editor or in the browser
* Starts a local server for the user
* Provides a basic logging console

### Future Plans
* Windows & Linux versions
* Integrated p5.js documentation and examples
* Update sketches live
* Support for mp4 and mp3

### Download
To get started, [download the editor here](https://github.com/antiboredom/jside/releases/latest), and visit [p5js.org](http://p5js.org) for more info on p5.js.

## Development

If you're interested in contributing to the devlopment of the editor, follow the direction below:

### Prerequisites

1. Node.js
2. Git

### Setup

1. Clone this repo: `git clone https://github.com/antiboredom/jside.git`
2. Enter the repo directory and install the development modules: `npm
   install`
3. Install secondary modules: `cd public` and then `npm install`
4. Install gulp.js globally: `npm install gulp -g`
5. From the root directory of the repo run gulp: `gulp`
6. Start up the app: `npm run app`

### Workflow

Most development takes place in the `app` folder. Gulp will watch the files in the app folder, then bundle them up with Browserfiy, and send the results to the `public` folder.

The public folder contains the `package.json` for the application window, as well as the base `index.html` file for the application.

Below you'll find documentation for the different libraries we're using
* [vue.js](http://vuejs.org/)
* [node-webkit](https://github.com/rogerwang/node-webkit/wiki)
* [browserify](http://browserify.org/)
* [gulp.js](http://gulpjs.com/)
