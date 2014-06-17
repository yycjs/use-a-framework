title: Why use a framework?
output: index.html
theme: theme
controls: false
logo: theme/logo.png

--

# Use a framework?

## Why... or why not...

## And how to find one

--

# Brought to you by

-- presenter

![David Luecke](http://gravatar.com/avatar/a14850281f19396480bdba4aab2d52ef?s=200)

## David Luecke

* [<i class="fa fa-github"></i> daffl](https://github.com/daffl)
* [<i class="fa fa-twitter"></i> @daffl](http://twitter.com/daffl)

-- presenter

![Eric Kryski](http://gravatar.com/avatar/23aba778a7daae99348aeb0728cf4aec?s=200)

## Eric Kryski

* [<i class="fa fa-github"></i> ekryski](https://github.com/ekryski)
* [<i class="fa fa-twitter"></i> @ekryski](http://twitter.com/ekryski)
* [<i class="fa fa-home"></i> erickryski.com](http://erickryski.com)

-- sponsors

# Our Sponsors

![Assembly](img/sponsors/assembly_logo.png)

![Village Brewery](img/sponsors/village_brewery_logo.png)

![Startup Calgary](img/sponsors/startup_calgary_logo.png)

![PetroFeed](img/sponsors/petrofeed_logo.png)

--

# Last Month

## Optimizing Your JS Workflow

* Modules and build tools
  * AMD + RequireJS
  * Component + Makefiles
  * Browserify
  * Grunt & Gulp
* Using Gulp + Browserify

--

# Today...

* A web developer story
  * JavaScript & jQuery
  * Modularity
  * Build tools
  * Package management
  * Framework
  * Testing
* InstaCan

--

# Once upon a time...

## ... there was a site with some plain JavaScript and maybe some jQuery plugins.

--

<script src="https://gist.github.com/daffl/43749f8e99a8e000a277.js"></script>

--

# Modularity

Split your appication into individual files. We talk more about it
in our __jQuery 202 session__ ([slides](http://yycjs.com/jquery-202-and-web-components/#slide1),
[video](https://www.youtube.com/watch?v=Bm9C7WvJOIk)).

```javascript
var APP = (function() {
	// Do stuff
	var privateVariable = 'Hello ',
		sayHi = function(name) {
			return privateVariable + name;
		};
	// Return API
	return {
		init : function() { /* ... */ },
		hi : sayHi
	}
})();
```
--

# Build tools

Build tools make your life way easier and allow you to dev faster. We talk more about them in our __Optimize Your Workflow session__ ([slides](http://yycjs.com/js-workflow/)).


<img src="img/browserify-logo.png" alt="Browserify logo" style="max-width: 400px; float: left; margin-top: 3em;">
<img src="img/grunt-logo.png" alt="Grunt logo" style="max-width: 200px; float: left; margin-top: 2em;">
<img src="img/gulp-logo.png" alt="Gulp logo" style="max-width: 200px; float: left;">

--

# Package management

A framework is only as good as its package manager. Thankfully we have good ones! We also talk about them in our __Optimize Your Workflow session__ ([slides](http://yycjs.com/js-workflow/)).

<img src="img/npm-logo.png" alt="npm logo" style="max-width: 300px; float: left; margin-top: 2em;">
<img src="img/bower-logo.png" alt="Bower logo" style="max-width: 200px; float: left; margin: 1em 1em;">
<img src="img/component-logo.jpg" alt="Component logo" style="max-width: 300px; float: left; margin-top: 2em;">

--

# Library vs. Framework

__Library__:

* A set of tools to reduce overhead and improve application consistency by providing reusable pieces of code.
* A library provides useful tools for a specific purpose (functions, helper libs) so you can build your app your way.

__Framework__:

* A **more opinionated** set of tools to reduce overhead and improve application consistency by providing reusable pieces of code.
* Inversion of control. Frameworks specify how you should write your app.

--

# Model View Controller

Separates the representation of information from the user's interaction with it
<img src="img/mvc.png" alt="MVC overview" style="float: right; margin-right: 2em; margin-top: 1em;" />

* __Controller__: Updates both, view and model according to user interaction
* __Model__: The data/domain model
* __View__: Creates a representation of the model

--

# [TodoMVC](http://todomvc.com/)

The same Todo application implemented using MV\* concepts in most of the popular JavaScript MV\*
frameworks of today.

<img src="img/todomvc.png" alt="TodoMVC" style="float: right; margin-right: 6em;" />

* Backbone
* CanJS
* Ember
* AngularJS
* React
* KnockoutJS
* ...

--

# You Don't Always Need a Framework

<img src="img/no-bootstrap.png" alt="No Bootstrap" style="width: 50%; float: right; margin-right: 6em;" />

* Web Pages
* Widgets
* Components
* Small applications

--

# What To Look For

Choosing a framework is like getting married. You'll probably be stuck with it for a loooong time. __Choose wisely__:

* Flexibility & Modularity
* Maintenance & Development Activity
* Community Support
* How big is your app actually going to get?
* Do you REALLY need everything that it provides?
* Developer culture
* Learning Curve
* Code Size

--

# Next Month

<img src="img/awesome-sauce.png" alt="Awesome Sauce" style="width: 50%; float: right; margin-right: 6em;" />

* Something awesome
* More awesomeness
* Even more awesome sauce
