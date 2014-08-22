Chrome Extension Boilerplate
============================

This is a boilerplate for Chrome app, extension, and theme development. It should be easy enough to get started even if you've never built a Chrome extension before by following the INSTALLATION notes.

[Chrome extension documentation](http://code.google.com/chrome/extensions). Icons auto-generated at [Faviconist](http://faviconist.com).

This repo is fully MIT-licensed.

## Installation ##

  The boilerplate works out of the box, so start by installing it in Chrome:

  - `cd ~/git/`
  - `git clone https://github.com/will-janz/chrome-boilerplate.git extension-name`
  - Visit chrome://extensions and expand "Development mode" (top right).
  - Choose "Load unpacked extension..." and point to the new project directory.
  - It's installed! You should see a new button in your address bar. Click it!
  
  From there you can make whatever changes you wish. To reload the extension, repeat the last two steps.

## Customization ##

  By default, most things are commented out - uncomment them to make them active.
  
  Your extension can be either an app, action, or theme. Trying to be more than one of those things will confuse Chrome.
  
  ### Permissions ###
  
    For convenience, these are mostly selected by default (except "experimental",
    as it requires you run Chrome with a special flag). Be sure to comment out
    what you don't need - i.e., most of them - before distributing your extension.

  ### Locales ###

    A basic locale setup is included, with English declared as the default
    language. This won't do any harm even if you're not planning to localize your app.

## Apps ##
  
  TODO: Go into detail about apps, app types, and app specifics.

## Actions ##
  
  TODO: Go into detail about actions, action types, and action specifics.

## Themes ##
  
  TODO: Go into detail about themes, their requirements, their non-requirements, etc.


## Credits ##
  
  Boilerplate originally created by [Michael Mahemoff](http://mahemoff.com), former Chrome dev. [Original repo](https://github.com/mahemoff/chrome-boilerplate)
