### Regular method

* Clone repo `git clone https://github.com/jeffreyvr/tailpress.git && cd tailpress`
* Run `rm -rf .git` to remove git (or `rmdir .git` for Windows)
* Run `npm install`
* Run `npm run watch` to start developing


## NPM Scripts

There are several NPM scripts available. You'll find the full list in the `package.json` file under "scripts". A script is executed through the terminal by running `npm run script-name`.

| Script     | Description                                                                    |
|------------|--------------------------------------------------------------------------------|
| production | Creates a production (minified) build of app.js, app.css and editor-style.css. |
| dev        | Creates a development build of app.js, app.css and editor-style.css.           |
| watch      | Runs several watch scripts concurrently.                                       |
| watch-sync | Runs several watch scripts concurrently and starts `browser-sync`.             |


## Links

* [TailPress website](https://tailpress.io)
* [Screencasts](https://www.youtube.com/playlist?list=PL6GBdOp044SHIOSCZejodwr1HcYsC43wG)
* [Tailwind CSS Documentation](https://tailwindcss.com/docs)
* [Esbuild Documentation](https://esbuild.github.io)
