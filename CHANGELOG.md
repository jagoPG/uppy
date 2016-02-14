Our combined changelog and todo. 

Items can be optionally be tagged tagged by GitHub owner issue if discussion
happened / is needed.

Please add your entries in this format:

 - `- [ ] (<plugin name>|website|core|meta|test): <Present tense verb> <subject> \(<list of associated owners/gh-issues>\)`.

Following [SemVer item 4](http://semver.org/#spec-item-4), we're `<1.0.0` and allowing ourselves to make breaking changes in minor patch levels.

In the current stage we aim to release a new version on the first Tuesday of every new month.

## TODO

Ideas that will be planned into a release at one point

- [ ] instagram: Add basic Instagram plugin example (#21)
- [ ] presets: Add basic preset that mimics Transloadit's jQuery plugin (#28)
- [ ] tus: Add support tus 1.0 uploading capabilities (#3)
- [ ] core: Apply plugins when DOM elements aren't static (#25)
- [ ] test: Write an acceptance test for the Multipart example via Saucelabs (#2, #23, @hedgerh)
- [ ] test: setup an HTML page with all sorts of crazy styles, resets & bootstrap to see what brakes Uppy

## 0.0.4 (April 05, 2016)


## 0.0.3 (March 01, 2016)

- [ ] test: Fix and enable phantom acceptance test. Write one actual test. Enable it in `npm run test` so it's ran on Travis automatically (@hedgerh)
- [ ] test: Fix and enable commented out `run one plugin success` unit test  (@arturi)
- [ ] core: Decide on single-noun terminology (npm, umd, dist, package, cdn, module, bundle), and call it that through-out.
- [ ] modal: Add basic Modal plugin that can be used as a target (#53, #50)
- [ ] google: Add basic Google Drive plugin example
- [ ] core: clean up package.json. We've accumulated duplication and weirdness by hacking just for our current problem without keeping a wider view of what was already there 
- [ ] core: Create a progressbar/spinner/etc plugin (#18)
- [ ] meta: Decide on tagline(s)
- [ ] meta: Create an Uppy logo (@vvolfy)
- [ ] server: Add a deploy target for uppy-server so we can use it in demos (#39, @kvz)

## 0.0.2 (February 11, 2016)

- [x] server: Create a (barely) working uppy-server (#39, @hedgerh)
- [x] core: implement a non-blocking `install` method (for Progressbar, for example)  (@arturi, @kvz)
- [x] dragdrop: Use templates, autoProceed setting, show progress (#50, #18, @arturi)
- [x] meta: Implement playground to test things in, templates in this case
- [x] core: Implement ejs or es6 templating (@arturi, @hedgerh)
- [x] core: Improve on `_i18n` support, add tests (#47, @arturi)
- [x] buildsystem: Use parallelshell and tweak browserify to work with templates (@arturi)
- [x] docs: Fix build-documentation.js crashes, add more docs to Utils and Translator (@arturi, @kvz)
- [x] core: Integrate eslint in our build procedure and make Travis fail on errors found in our examples, Core and Plugins, such as `> 100` char lines (@kvz)
- [x] core: Add basic i18n support via `core.translate()` and locale loading (#47, @arturi)
- [x] website: Fix Uppy deploys (postcss-svg problem) (@arturi, @kvz)

## 0.0.1 (December 20, 2015)

- [x] dragdrop: Add basic DragDrop plugin example (#7)
- [x] dropbox: Add basic Dropbox plugin example (#31)
- [x] website: Add CSS Framework (#14)
- [x] website: Create Hexo site that also contains our playground (#5, #34, #12 #22, #44, #35, #15, #37, #40, #43)
- [x] core: Individual progress (#24)
- [x] core: Setup basic Plugin system (#1, #4, #20)
- [x] core: Setup build System (#30, #13, @hedgerh)