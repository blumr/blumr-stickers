# Blumr Stickers
Image stickers

### Maintainers
* Gene Diaz Jr. <gene@letsblumit.com>
* Glenn Michael Echavez <makoy@letsblumit.com>

### Technologies
* [svgo](https://github.com/svg/svgo/) - svg optimizer
* [svg2png](https://github.com/domenic/svg2png) - converter

### Configs
* [.jscsrc](http://jscs.info/rules.html) - javascript code style
* [.jshintrc](http://jshint.com/docs/options/) - javascript code quality
* [.gitignore](http://git-scm.com/docs/gitignore) - git ignored dirs and files
* [package.json](https://docs.npmjs.com/files/package.json) - project details through nodejs

### Contributing
Make sure that [nodejs is installed](http://nodejs.org/download/) first.
For osx, its best to [use homebrew](http://shapeshed.com/setting-up-nodejs-and-npm-on-mac-osx/).

#### Install dependencies
```
npm install
```

#### Clean SVGs
```
npm run clean
```

#### Convert SVGs
```
npm run convert
```

### Roadmap
*

#### Project directory structure
```
├─ 256x256  - minified
├─ demo     - stickers demo
├─ png      - raw pngs
└─ svg      - source svgs
```

### License
* All codes are under [MIT License](https://github.com/letsblumit/blumr-stickers/blob/master/LICENSE-CODE)
* All graphics are under [Creative Commons Attribution 4.0 International CC-BY 4.0](https://github.com/letsblumit/blumr-stickers/blob/master/LICENSE-GRAPHICS)

