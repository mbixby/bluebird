Download `Better Coffeescript` via Package Manager and replace the `CoffeeScript.tmLanguage` file. If you want a fork of Better Coffeescript instead, open an issue.

### `CoffeeScript.tmLanguage` diff

* removes identification of functions for built-in JS classes
* object properties are now included in symbol list (Cmd/Ctrl+R)
* support for Ember.js
* various minor fixes

### `CoffeeScript (modified for OOP).tmLanguage` diff

* same as above, plus:
* only identifies *top-level* functions and class properties to discourage superfluous nesting – the goal is to support good OOP principles through visual patterns (see [Github Notes preview](https://raw.github.com/mbixby/github-notes-color-scheme/master/preview/coffee.png))
* Mocha's `describe`, `it` are identified as keywords
* various minor fixes
