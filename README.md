#[Font Awesome v5.0.0](http://fontawesome.io)
###The iconic font and CSS framework

Font Awesome is a full suite of 585 pictographic icons for easy scalable vector graphics on websites,
created and maintained by [Dave Gandy](http://twitter.com/davegandy).
Stay up to date with the latest release and announcements on Twitter:
[@fontawesome](http://twitter.com/fontawesome).

Get started at http://fontawesome.io!

##License
- The Font Awesome font is licensed under the SIL OFL 1.1:
  - http://scripts.sil.org/OFL
- Font Awesome CSS, LESS, and Sass files are licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- The Font Awesome documentation is licensed under the CC BY 3.0 License:
  - http://creativecommons.org/licenses/by/3.0/
- Attribution is no longer required as of Font Awesome 3.0, but much appreciated:
  - `Font Awesome by Dave Gandy - http://fontawesome.io`
- Full details: http://fontawesome.io/license

##Changelog

## Contributing

Please read through our [contributing guidelines](https://github.com/FortAwesome/Font-Awesome/blob/master/CONTRIBUTING.md).
Included are directions for opening issues, coding standards, and notes on development.

##Versioning

Font Awesome will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered
with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org.

##Author
- Email: dave@fontawesome.io
- Twitter: http://twitter.com/davegandy
- GitHub: https://github.com/davegandy

##Component
To include as a [component](http://github.com/component/component), just run

    $ component install FortAwesome/Font-Awesome

Or add

    "FortAwesome/Font-Awesome": "*"

to the `dependencies` in your `component.json`.

## Hacking on Font Awesome

**Before you can build the project**, you must first have the following installed:

- [Ruby](https://www.ruby-lang.org/en/)
- Ruby Development Headers
  - **Ubuntu:** `sudo apt-get install ruby-dev` *(Only if you're __NOT__ using `rbenv` or `rvm`)*
  - **Windows:** [DevKit](http://rubyinstaller.org/)
- [Bundler](http://bundler.io/) (Run `gem install bundler` to install).
- [Node Package Manager (AKA NPM)](https://docs.npmjs.com/getting-started/installing-node)
- [Less](http://lesscss.org/) (Run `npm install -g less` to install).
- [Less Plugin: Clean CSS](https://github.com/less/less-plugin-clean-css) (Run `npm install -g less-plugin-clean-css` to install).

From the root of the repository, install the tools used to develop.

    $ bundle install
    $ npm install

Build the project and documentation:

    $ bundle exec jekyll build

Or serve it on a local server on http://localhost:7998/Font-Awesome/:

    $ bundle exec jekyll -w serve
