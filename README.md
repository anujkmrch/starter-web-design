# Starter Web Design

This is the quick start web design development directory for you,

## Getting Started

Download a clone to your system

### Prerequisites

Any modern browser and an internet connnection, if you do no have internet connection use the local normalize.css like below

```
<link type="text/css" rel="stylesheet" href="/css/normalize.css" />
```
if you're interested in another framework you can use any reset framework,

### Recommended extras
1. Sublime text editor,
2. Emmet package in sublime text

### Installing

Clone the file and extract anywhere you can access it easily, I guess desktop is the best place to start

Drag the parent folder in your favorite text editor, i already recommended sublime, to see the project directory but not necessary,
you can use the basic ones vim linux or note in windows, totally depends on you.

Also open the index.html file in your favorite browser.


## Running the tests

When you open the browser you will see the html file into it. Every time you make changes into it,, just refresh the page and you can see the changes.

## Styling the web design

If you're familiar with sass then you can do the code the scss/style.scss file

the compiled stylesheets are in css/style.css which a browser uses to style the website

To use sass, use
```
sass --watch scss/style.css:css/style.css
```
To create the minified version of the css, use
```
sass --watch scss/style.scss:css/style.css --style compressed
```
