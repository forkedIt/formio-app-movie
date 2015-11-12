Example movie application using Form.io
---------------------------------
This is an example project that integrates into Form.io.

Installation
--------------

New Project
===========
If you have not yet created a project on Form.io, you can easily create one and get this application running by typing the following in your command line:

```
npm install -g formio-cli
formio bootstrap formio/formio-app-movie
```

This will create a project for you on Form.io as well as configure this application to use your sandboxed project. Feel free to fork and modify as you like.

Existing Project
================
To hook this up to an existing project, clone this repository (or download the .zip on the right), and edit the `APP_URL` in `src/config.js` to match your project's url. For example, if your project name is `myproject`, then your project url would be `https://myproject.form.io`.

Building
--------
Make sure you have installed the dependencies:

```
npm install -g grunt-cli bower
gem update --system
gem install compass
npm install
bower install
```

Run `grunt serve` to spin up a web server for development. `grunt build` will create a production ready build in `dist/`.
