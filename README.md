# Corey Warren

> Portfolio of Corey Warren

This project was created using the [grunt-neat-pages](https://github.com/jpdevries/grunt-neat-pages/) boilerplate.
[Sass](http://sass-lang.com/) is used to pre-process CSS.

### Includes:

 - [HTML5 Boilerplate](http://html5boilerplate.com/)
 - [Bourbon](http://bourbon.io/)
 - [Neat](http://neat.bourbon.io/)
 - [Font-Awesome](http://fortawesome.github.io/Font-Awesome/)
 
Contribution Guides
--------------------------------------

The visual design of coreyswarren.com is developed using Sass and Grunt to allow front end developers to quickly create custom themes and contribute to the core. In the spirit of open source software development, we always encourages community code contribution. To help you get started and before you jump into writing code, be sure to read these important contribution guidelines thoroughly.

What you need
--------------------------------------

In order to build coreyswarren.com front end assets, you need to have Ruby, Node.js/npm latest and git 1.7 or later.
(Earlier versions might work OK, but are not tested.)

For Windows you have to download and install [git](http://git-scm.com/downloads) and [Node.js](http://nodejs.org/download/).

Mac OS users should install [Homebrew](http://mxcl.github.com/homebrew/). Once Homebrew is installed, run `brew install git` to install git,
and `brew install node` to install Node.js.

Linux/BSD users should use their appropriate package managers to install git and Node.js, or build from source
if you swing that way. Easy-peasy.

Installing Ruby and Ruby Gems
----------------------------
You'll need ruby and sass gems installed. If you're on OS X or Linux you probably already have Ruby installed; test with ruby -v in your terminal. When you've confirmed you have Ruby installed, run gem install sass to install Sass.

```bash
gem install sass
```

Make sure you have `sass` installed by testing:

```bash
sass --version
```
_Note: Depending on your ruby setup you may need to install gems using `sudo gem install sass`._

Installing Grunt & Grunt Packages
----------------------------

First, [clone a copy of this git repo](github-mac://openRepo/https://github.com/jpdevries/coreyswarren) by running:

```bash
git clone git://github.com/jpdevries/coreyswarren.git
```

Install the [grunt-cli](http://gruntjs.com/getting-started#installing-the-cli) package if you haven't before. These should be done as global installs:

```bash
npm install -g grunt-cli
```

Make sure you have `grunt` installed by testing:

```bash
grunt --version
```

Enter the default template directory and install the Node dependencies, this time *without* specifying a global(-g) install:

```bash
cd coreyswarren/_build/templates/default
npm install
```
_Note: `npm install` updates dependencies and should be run whenever you pull from git._

Optionally enable Growl notifications install [terminal-notifier](https://github.com/alextucker/grunt-growl#getting-started) with RubyGems:
```bash
gem install terminal-notifier
```
_Note: Depending on your ruby setup you may need to install gems using `sudo gem install terminal-notifier`._

Grunt Commands
----------------------------

__Build__<br>
Fetch dependencies (such as bourbon), move items into place and compile by running:

```bash
grunt build
```

__Watch__<br>
Compile the Sass and watch files for changes type the following:

```bash
grunt
```
_Note: grunt is now watching files for changes. When Sass files are changed CSS will automatically be generated.<br>Install the LiveReload [browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-) to inject CSS changes without a page refresh._

__Expand__<br>
Compile Sass using expanded output style for development by running:

```bash
grunt expand
```
_Note: do not check in uncompressed CSS._

 
