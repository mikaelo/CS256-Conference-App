Udacity Conf
============

So you want to run this thing?  We use Grunt (http://gruntjs.com/) for build steps, so you need to:

- install [NodeJS](http://nodejs.org/)
- install [Grunt](http://gruntjs.com/) using the command `npm install -g grunt-cli`
- run `grunt server` in the top-level directory of the app to test out on a local server.

This should automatically load the page in your browser. Instead of running `grunt server`, you can also try:

- running `grunt build` in the top-level directory of the app.
- run the Google AppEngine Launcher in the `dist/` directory that was created by the `grunt build` command
- open the page in your browser on `localhost`

You get the following with Grunt
- Live Reload, changes saved to your project will automatically reload the browser page if you're running `grunt server`.
- Auto-Prefixing (i.e. display: flex; will be old and new flexbox standards AND get vendor prefixed)
- Loads of other cool and useful stuff.... ;)
- Check out `Gruntfile.js` in order to check it out. Not the easiest going, but useful to learn.
