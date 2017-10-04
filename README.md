## Setting up a workflow and using SASS
First steps outlined in screen shots, file structures outlined.
set up `package.json` file with the code below:  
```json
{
  "name": "rouxmeetups",
  "version": "0.0.1",
  "dependencies": {
    "grunt": "~0.4.1",
    "grunt-contrib-watch": "~0.5.3",
    "grunt-contrib-compass": "~0.5.0",
    "grunt-contrib-uglify": "~0.2.2",
    "matchdep": "0.1.2"
  }
}
```

Run `npm install` in your terminal  
#### Create `gruntfile.js` see my file
Added `uglify` and `watch` and automatic reloading