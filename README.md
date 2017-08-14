# Artemis

This is a customized [Hexo](http://hexo.io) theme forked from [Dreyer/hexo-theme-artemis](https://github.com/Dreyer/hexo-theme-artemis), which is based on theme [pinggod/hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo).

## Added / Modified Features

- Fix logo alignment and content margin on mobile screen.
- Add tags and categories of posts.
- Change colors to dark theme.
- Highlight code block with [Ocean theme](https://github.com/isagalaev/highlight.js/blob/master/src/styles/ocean.css)
- Replace theme dev-dependency [grunt-contrib-sass](https://github.com/gruntjs/grunt-contrib-sass) with [grunt-sass](https://github.com/sindresorhus/grunt-sass), which compiles SASS to CSS in Node.js. No need of Ruby anymore.

**For other original features and configs, please refer to [Artemis](https://github.com/Dreyer/hexo-theme-artemis) and [Apollo](https://github.com/pinggod/hexo-theme-apollo).**


## Setup

### Install

Install dependencies. This theme renders html layout from `.pug` files. 

```bash
npm install --save hexo-renderer-pug hexo-generator-feed hexo-generator-sitemap
```

Then `cd` to your hexo project folder. Clone repo to path theme/artemis.
```bash
git clone https://github.com/yuugou727/hexo-theme-artemis.git themes/artemis
```

### Enable

In `_config.yml`, change `theme` to `artemis`.

## Development - Complie SASS

Inside `/artemis` folder, install dependencies.

```bash
npm install
```

There are two avaliable commands to complie `/scss` to `source/css/theme.css`:

- `npm run watch` - watch `.scss` files' change and build instantly
- `npm run build` - build for once


## Credits

>This theme is largely based on the efforts of [Sean Sun](https://github.com/pinggod).
> -- [README of Artemis](https://github.com/Dreyer/hexo-theme-artemis/blob/master/README.md)

And this custom theme is based on the efforts of [Matthew Dreyer](https://github.com/Dreyer), 

>According to classical Greek mythology, [Artemis](https://en.wikipedia.org/wiki/Artemis) is the twin sister of Apollo and as this theme is virtually identical to [hexo-theme-apollo](https://github.com/pinggod/hexo-theme-apollo) ...

While Apollo is the god of sun, Artemis is the goddess of moon. So I make this to a dark theme.

## License

MIT