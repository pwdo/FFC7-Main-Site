FFC7 Main Site
=============================

## Development

### Jekyll

This site uses [Jekyll](http://jekyllrb.com) as it's site generator. So if you want to see how the site works on your local device, you're required to install Jekyll.

1. Make sure you have Ruby(v2.0.0 at least) installed.
2. Install Jekyll with `gem install jekyll`
3. To run Jekyll, type `jekyll serve` and hit enter.
4. Head over to [127.0.0.1:4000](http://127.0.0.1:4000).
5. To stop Jekyll from watching the files and running the server, just hit `control + c`

### Grunt

The site uses [Grunt](http://gruntjs.com) to watch and compile all the Sass and Javascript files.

#### First time
If this is your first time running Grunt after installing all the Bower dependencies, you'll have to run the following to compile the plugin scripts into `js/plugin.min.js`, since the `grunt` command will only compile the `js/dev/main.js`.

1. Go to the root directory of the project.
2. Type `npm install`.
3. Now Grunt and all other dependencies will be installed inside `node_modules`.
4. Run `grunt js`.

#### Normal usage

1. Go to the root directory of the project.
2. Type `npm install`.
3. Now Grunt and all other dependencies will be installed inside `node_modules`.
4. Go ahead and run `grunt`.