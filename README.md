# Awesome npm [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 🌎 [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](www.npmjs.com)

> Awesome 🌎 [npm](www.npmjs.com) resources and tips

[npm](https://en.wikipedia.org/wiki/Npm_(software)) is a package manager for the JavaScript programming language and comes bundled in the 🌎 [Node.js](en.wikipedia.org/wiki/Node.js) runtime.

*Please read the [contribution guidelines](contributing.md) before contributing.*

## Contents

- [Articles](#articles)
- [Tools](#tools)
- [Packages](#packages)
- [Clients](#clients)
- [Tips](#tips)
- [FAQ](#faq)
- [Community](#community)
- [Documentation](#documentation)
- [Support](#support)
- [Related](#related)

## Articles

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328))
- [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.
- 🌎 [Writing small modules](web.archive.org/web/20180302125059/https://substack.net/how_I_write_modules)
- 🌎 [Semver: A Primer](nodesource.com/blog/semver-a-primer/) *(Must read!)*
- 🌎 [Semver: Tilde and Caret](nodesource.com/blog/semver-tilde-and-caret/)
- 🌎 [Offline installation of npm packages](addyosmani.com/blog/using-npm-offline/)
- 🌎 [Task automation with npm run](web.archive.org/web/20180302164842/http://substack.net/task_automation_with_npm_run)
- 🌎 [How to use npm as a build tool](www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- <b><code>&nbsp;&nbsp;2516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;448🍴</code></b> [Install npm packages globally without sudo on macOS and Linux](https://github.com/sindresorhus/guides/blob/main/npm-global-without-sudo.md))
- 🌎 [Optimizing the footprint of an npm package](medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- <b><code>&nbsp;&nbsp;9892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;850🍴</code></b> [The Art of Node](https://github.com/maxogden/art-of-node#modules)) - An introduction to Node.js and client-side development with npm.
- 🌎 [Why npm scripts?](css-tricks.com/why-npm-scripts/) - An introduction to npm scripts with common packages and scripts, as well as a boilerplate project.

## Tools

### Web

- 🌎 [npms](npms.io) - Superb package search with deep analysis of package quality using a 🌎 [myriad of metrics](npms.io/about).
- 🌎 [NodeICO](nodei.co/) - Package badges.
- 🌎 [Libraries.io](libraries.io/npm) - Package discovery.
- [npm-stat](http://npm-stat.com) - Statistics charts for packages.
- [npmgraph](http://npm.anvaka.com) - Visualization of dependencies.
- [npm trends](http://www.npmtrends.com) - Compare package download counts over time.
- 🌎 [npm-top](gist.github.com/bcoe/dcc961b869bbf6685002) - npm users by downloads.
- [npm semver calculator](http://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
- 🌎 [ghub.io](ghub.io) - Redirects to the GitHub repo of an npm package.
- 🌎 [moiva](moiva.io) - Discover and compare packages.

### Browser extensions

- 🌎 [Octo-Linker](chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension to navigate across npm packages on GitHub with ease.
- 🌎 [npm-hub](chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to explore npm dependencies on GitHub repos.
- 🌎 [github-npm-stats](chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - View npm download stats on GitHub.
- 🌎 [npm-search-update](chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - Chrome extension to quickly search for dependencies and monitor changes from the npm registry.

### CLI

- <b><code>&nbsp;&nbsp;&nbsp;496⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion)) - Better ZSH completion for npm.
- <b><code>&nbsp;&nbsp;9066⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;226🍴</code></b> [npkill](https://github.com/voidcosmos/npkill)) - Easily find and remove old and heavy node_modules folders.

## Packages

### Publishing

- <b><code>&nbsp;&nbsp;7683⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;311🍴</code></b> [np](https://github.com/sindresorhus/np)) - A better `npm publish`.
- <b><code>&nbsp;&nbsp;&nbsp;738⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [publish-please](https://github.com/inikulin/publish-please)) - Publish packages safely and gracefully.
- <b><code>&nbsp;&nbsp;&nbsp;103⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [npm-release](https://github.com/phuu/npm-release)) - Making releasing to npm so easy a kitten could probably do it™.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [pkgfiles](https://github.com/timoxley/pkgfiles)) - List all files which would be published in a package.
- <b><code>&nbsp;&nbsp;8850⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;552🍴</code></b> [release-it](https://github.com/webpro/release-it)) - Automate releases for Git repositories and/or npm packages. Changelog generation, GitHub/GitLab releases, etc.
- <b><code>&nbsp;23336⭐</code></b> <b><code>&nbsp;&nbsp;1794🍴</code></b> [semantic-release](https://github.com/semantic-release/semantic-release)) - Fully automated package publishing.

### Registry

- <b><code>&nbsp;&nbsp;&nbsp;288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [npm-name](https://github.com/sindresorhus/npm-name-cli)) - Check whether a package name is available on npm.
- <b><code>&nbsp;&nbsp;&nbsp;247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [package-json](https://github.com/sindresorhus/package-json)) - Get the package.json of a package from the npm registry.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [latest-version](https://github.com/sindresorhus/latest-version-cli)) - Get the latest version of an npm package.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [npm-keyword](https://github.com/sindresorhus/npm-keyword)) - Get a list of npm packages with a certain keyword.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [npm-user](https://github.com/sindresorhus/npm-user)) - Get user info of an npm user.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [npm-email](https://github.com/sindresorhus/npm-email)) - Get the email of an npm user.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [npm-user-packages](https://github.com/kevva/npm-user-packages-cli)) - Get packages by an npm user.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [dpn](https://github.com/gillstrom/dpn)) - Get the dependents of a user's npm packages.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [npm-stats](https://github.com/hughsk/npm-stats)) - Get data from an npm registry.
- <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [npm-cli-login](https://github.com/postmanlabs/npm-cli-login)) - Log in to npm.
- <b><code>&nbsp;&nbsp;2997⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;254🍴</code></b> [nrm](https://github.com/Pana/nrm)) - Registry manager.
- <b><code>&nbsp;&nbsp;&nbsp;484⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [npm-register](https://github.com/dickeyxxx/npm-register)) - Easy to set up and maintain npm registry and proxy.
- <b><code>&nbsp;17486⭐</code></b> <b><code>&nbsp;&nbsp;1449🍴</code></b> [verdaccio](https://github.com/verdaccio/verdaccio)) - Lightweight private npm proxy registry.
- 🌎 [cloudsmith](cloudsmith.io/l/npm-registry/) - A fully managed package management SaaS with support for public and private npm registries (and many others).
- 🌎 [RepoFlow](www.repoflow.io) - A simple and easy-to-use package management platform, available for both cloud and self-hosted deployments.

### Other

- <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [npm-home](https://github.com/sindresorhus/npm-home)) - Open the npm page of a package.
- <b><code>&nbsp;&nbsp;&nbsp;193⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [gh-home](https://github.com/sindresorhus/gh-home)) - Open the GitHub page of a package.
- <b><code>&nbsp;&nbsp;&nbsp;968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [david](https://github.com/alanshaw/david)) - Check if your package dependencies are out of date.
- <b><code>&nbsp;&nbsp;6643⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [npm-check](https://github.com/dylang/npm-check)) - Check for outdated, incorrect, and unused dependencies, as well as interactive update.
- <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [npm-upgrade](https://github.com/th0r/npm-upgrade)) - Update outdated npm dependencies interactively.
- <b><code>&nbsp;&nbsp;&nbsp;771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap)) - A consistent shrinkwrap tool.
- <b><code>&nbsp;&nbsp;2516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade)) - Upgrade npm on Windows.
- <b><code>&nbsp;&nbsp;&nbsp;740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [generator-nm](https://github.com/sindresorhus/generator-nm)) - Scaffold out an npm package.
- <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [package-up](https://github.com/sindresorhus/package-up)) - Find the closest package.json file.
- <b><code>&nbsp;&nbsp;&nbsp;268⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [read-package-up](https://github.com/sindresorhus/read-package-up)) - Read the closest package.json file.
- <b><code>&nbsp;&nbsp;&nbsp;204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [normalize-package-data](https://github.com/npm/normalize-package-data)) - Normalize package metadata.
- <b><code>&nbsp;&nbsp;&nbsp;121⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [package-config](https://github.com/sindresorhus/package-config)) - Get namespaced config from the closest package.json.
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [npm-run-path](https://github.com/sindresorhus/npm-run-path)) - Run locally installed binaries in the terminal by name like with global ones.
- <b><code>&nbsp;&nbsp;1170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81🍴</code></b> [local-npm](https://github.com/nolanlawson/local-npm)) - Use npm 🌎 [offline](addyosmani.com/blog/using-npm-offline/).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [npe](https://github.com/zeke/npe)) - CLI for inspecting and editing properties in package.json.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [engine-deps](https://github.com/samccone/engine-deps)) - Manage Node.js version specific dependencies with ease.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [enpeem-search](https://github.com/amovah/enpeem-search)) - Search packages by scraping the npm web search.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [npm-issues](https://github.com/seanzarrin/npm-issues)) - Search known issues of all your packages at once.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [john](https://github.com/davej/john)) - Make npm3's flat dependencies easier to find and sort.
- <b><code>&nbsp;&nbsp;&nbsp;957⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ntl](https://github.com/ruyadorno/ntl)) - Interactive CLI menu to list & run npm tasks.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [decheck](https://github.com/egoist/decheck)) - Explore dependencies of npm packages in the command-line.
- <b><code>&nbsp;&nbsp;&nbsp;805⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [shrinkpack](https://github.com/JamieMason/shrinkpack)) - Lock down your dependencies and install offline.
- <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [redrun](https://github.com/coderaiser/redrun)) - Expand scripts from package.json to improve execution speed.
- <b><code>&nbsp;&nbsp;&nbsp;426⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [package-size](https://github.com/egoist/package-size)) - Get the bundle size of an npm package.
- <b><code>&nbsp;&nbsp;&nbsp;783⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [synp](https://github.com/imsnif/synp)) - Convert yarn.lock to package-lock.json and vice versa.
- <b><code>&nbsp;&nbsp;5842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [npm-run-all](https://github.com/mysticatea/npm-run-all)) - CLI tool to run multiple npm-scripts in parallel or serial.
- <b><code>&nbsp;&nbsp;&nbsp;830⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [onchange](https://github.com/Qard/onchange)) - Watch files and folders and run a command when something changed.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [cli-error-notifier](https://github.com/micromata/cli-error-notifier)) - Sends native desktop notifications when npm scripts fail.
- <b><code>&nbsp;&nbsp;1006⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [luna](https://github.com/rvpanoz/luna)) - App to manage npm dependencies.
- <b><code>&nbsp;&nbsp;1244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [emma-cli](https://github.com/maticzav/emma-cli)) - Interactive CLI package search utility.
- <b><code>&nbsp;&nbsp;&nbsp;840⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [lockfile-lint](https://github.com/lirantal/lockfile-lint)) - Lint lockfiles for improved security and trust policies to mitigate malicious package injection and insecure lockfile resources.

## Clients

- <b><code>&nbsp;41540⭐</code></b> <b><code>&nbsp;&nbsp;2732🍴</code></b> [yarn](https://github.com/yarnpkg/yarn)) - Fast, reliable, and secure dependency management.
- <b><code>&nbsp;&nbsp;9540⭐</code></b> <b><code>&nbsp;&nbsp;4164🍴</code></b> [npm](https://github.com/npm/cli)) - The official client.
- <b><code>&nbsp;34123⭐</code></b> <b><code>&nbsp;&nbsp;1327🍴</code></b> [pnpm](https://github.com/pnpm/pnpm)) - Fast, disk space efficient package manager.

## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*<b><code>&nbsp;&nbsp;2516⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade))*

### Command aliases

- `npm i ` → `npm install`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install && npm test`
- `npm r` → `npm uninstall`
- `npm un` → `npm uninstall`
- `npm up` → `npm update`

### Shell aliases

Speed up your common npm tasks.

In your `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias ns='npm start'
alias nf='npm cache clean && rm -rf node_modules && npm install'
alias nlg='npm list --global --depth=0'
```

### Don't add to package.json when installing

By default npm adds packages you install to the `dependencies` field in package.json (since v5). You can prevent this by specifying the `--no-save` flag. You can add a package to `devDependencies` with `--save-dev`/`-D`:

```
$ npm install --save-dev ava
```

### Run scripts

You can easily 🌎 [run scripts](docs.npmjs.com/cli/run-script) using npm by adding them to the `"scripts"` field in package.json and run them with `npm run <script-name>`. Run `npm run` to see available scripts. Binaries of locally install packages are made available in the [PATH](https://en.wikipedia.org/wiki/PATH_(variable)), so you can run them by name.

```json
{
	"name": "awesome-package",
	"scripts": {
		"cat": "cat-names"
	},
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

```
$ npm run cat
Max
```

All package.json properties are 🌎 [exposed](docs.npmjs.com/misc/scripts#packagejson-vars) as environment variables:

```json
{
	"name": "awesome-package",
	"scripts": {
		"name": "echo $npm_package_name"
	}
}
```

```
$ npm run name
awesome-package
```

#### Passing options to commands

You can pass options to the command you are using in your npm script by adding `-- --flag` like in the example below. The `--` 🌎 [marks the end of options parsing](unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-dash), so `npm run` will just ignore it and pass it to the command.

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo -- --fix",
	}
}
```

*Adding the `-- --fix ` option is like executing `xo --fix`*.

#### Silent option

`npm run` has a `--silent` option which is especially useful when combining npm scripts.

Imagine you have a setup for linting your JavaScript files like the following:

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo --silent -- --fix",
	}
}
```

*Using the `--silent` option reduces the output in the terminal. See 🌎 [this comparison](twitter.com/mkuehnel/status/957965749473210369).*

### Lifecycle scripts

npm comes with predefined 🌎 [lifecyle scripts](docs.npmjs.com/misc/scripts) which are excuted under specific conditions if they are defined in your package.json.

```json
{
	"name": "awesome-package",
	"scripts": {
		"prepublishOnly": "nsp check"
	},
	"devDependencies": {
		"nsp": "^3.0.0"
	}
}
```

This will be executed automatically before your npm package is published to the registry via `npm publish` to check for known vulnerabilties in your dependencies.

*Note: **prepublishOnly** is available since npm v4.0.0. See 🌎 [npm docs](docs.npmjs.com/misc/scripts#deprecation-note).*

#### `npm start` and `npm test`

`npm start` and `npm test` are also lifecycle scripts but are not executed automatically.

```json
{
	"name": "awesome-package",
	"scripts": {
		"start": "node server.js",
		"test": "ava"
	},
	"devDependencies": {
		"ava": "^1.0.0"
	}
}
```

Therefore they can be executed simply with:

```console
$ npm test
$ npm start
```

#### `pre` and `post` scripts

These are special lifecycle scripts which can be used to run scripts automatically in sequence.

```json
{
	"name": "awesome-package",
	"scripts": {
		"pretest": "eslint .",
		"test": "ava"
	},
	"devDependencies": {
		"eslint": "^4.19.0",
		"ava": "^1.0.0"
	}
}
```

```console
$ npm test
```

This will lint your files before running your tests. The tests will not run if linting fails. Or more generally spoken: the following script won’t be executed if one of the scripts running in sequence exits with an exit code other than 0.

*Note: `pre` and `post` scripts can also be used for your custom npm scripts. So `npm run foo` will also run `prefoo` and `postfoo` if defined.*

### Run script with `npx`

`npm` 🌎 [comes bundled](medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) with `npx` (Since v5.2.0) — a tool to execute package binaries. Each command is executed either from the local `node_modules/.bin` directory, or from a central cache, installing any packages needed in order for `<command>` to run.

```json
{
	"name": "awesome-package",
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

If the binary is already installed, it will be executed from `node_modules/.bin`.

```
$ npx cat-names
Max
```

But if the binary is missing, it will be installed first.

```
$ npx dog-names
npx: installed 46 in 3.136s
Bentley
```

### Run commands with different Node.js versions

With `npx` (Comes bundled with npm v5.2.0 or newer) and the 🌎 [`node-bin`](www.npmjs.com/package/node-bin) package, you can easily try out code in different Node.js versions without having to use a version manager like [`nvm`](http://nvm.sh), <b><code>&nbsp;&nbsp;1629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [`nave`](https://github.com/isaacs/nave)), or <b><code>&nbsp;19509⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;762🍴</code></b> [`n`](https://github.com/tj/n)).

```
$ npx --package=node-bin@6.11.0 -- node --version
v6.11.0
```

### Link local packages

Sometimes it can be useful to have a local version of a package as a dependency. You can use `npm link` to link one local package into another. Run `npm link` in the package you want to use. This creates a global reference. Then go into your original package and run `npm link <package-name>` to link in the other package.

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

You can now use `rainbow` as a dependency in the `unicorn` package.

### Install a package from GitHub

npm supports using a shorthand for installing a package directly from a GitHub repo:

```
$ npm install sindresorhus/chalk
```

Let's target a specific commit as the main branch is a moving target:

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

Specify either a commit SHA, branch, tag, or nothing.

You can also install Git dependencies with semver: *(Requires npm v5 or newer)*

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### Install a specific version of a package

```
$ npm install chalk@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth=0
```

### Command help

Get help docs for a command:

```
$ npm help <command>
```

Example:

```
$ npm help install
```

### Standalone version of a package

Quickly get a standalone version of a package that is browserified and usable in the browser.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

- <https://wzrd.in/standalone/object-assign>
- <https://wzrd.in/standalone/object-assign@4.0.0>

Great for prototyping, but download the file or use Browserify yourself for production.

## FAQ

- [Check in node_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)

## Community

- [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
- 🌎 [Stack Overflow](stackoverflow.com/questions/tagged/npm)
- 🌎 [Reddit](www.reddit.com/r/npm)
- 🌎 [Twitter](twitter.com/npmjs)
- 🌎 [Blog](blog.npmjs.org)

## Documentation

- 🌎 [Official](docs.npmjs.com)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting))
- 🌎 [Semantic versioning](docs.npmjs.com/getting-started/semantic-versioning)
- 🌎 [Fixing npm permissions](docs.npmjs.com/getting-started/fixing-npm-permissions)
- 🌎 [package.json](docs.npmjs.com/files/package.json)
- 🌎 [npm run script](docs.npmjs.com/cli/run-script)
- <b><code>&nbsp;&nbsp;&nbsp;331⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Stats API](https://github.com/npm/download-counts))

## Support

- 🌎 [npm.community](npm.community/c/support)
- 🌎 [Twitter](twitter.com/npm_support)
- 🌎 [Contact form](www.npmjs.com/support)

## Related

- <b><code>&nbsp;65063⭐</code></b> <b><code>&nbsp;&nbsp;6183🍴</code></b> [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs))

## Source
<b><code>&nbsp;&nbsp;4673⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;275🍴</code></b> [sindresorhus/awesome-npm](https://github.com/sindresorhus/awesome-npm))