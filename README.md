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
Make sure my gems are all up to date, run `gem update system`. 
Create `config.rb` file - see file.
Run `gem instally susy` - I hadn't done this, the CSS wasn't compiling.  
Did `gem install compass`
Altered `gruntfile`, see file.
Great emmet tip! Type `meta:vp` to get the full viewport tag!!!  

### SASS  
`styles.scss` will have the imports, `base.scss` will contain basic SASS such as font information etc. The author recommends this setup:
<ul>
    <li>`_base.scss`</li>
    <li>`_layout.scss`</li>
    <li>`_mixins.scss`</li>
    <li>`_modules.scss`</li>
    <li>`_variables.scss`</li>
</ul>