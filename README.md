# grunt-download-atom-shell

Download atom-shell.

## Installation

Install npm package, next to your project's `Gruntfile.js` file:

```sh
npm install git+ssh://git@github.com:atom/grunt-download-atom-shell.git
```

Add this line to your project's `Gruntfile.js`:

```js
grunt.loadNpmTasks('grunt-download-atom-shell');
```

## Options

* `version` - **Required** The version of atom-shell you want to download.
* `outputDir` - **Required** Where to put the downloaded atom-shell.
* `downloadDir` - Where to find and save cached downloaded atom-shell.
* `symbols` - Download debugging symbols instead of binaries, default to `false`.
* `rebuild` - Whether to rebuild native modules after atom-shell is downloaded.
* `apm` - The path to apm.
