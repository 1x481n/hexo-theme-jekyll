# Hexo Theme ： Jekyll

> A hexo theme inspire by jekyllrb.com

## Never Support 

- Comment System

## Plan

- Support responsive
- Support zh-cn/en

## Install

``` bash
$ hexo init Blog && cd Blog && npm install
$ npm install --save hexo-renderer-jade hexo-generator-feed
$ git clone https://github.com/pinggod/hexo-theme-jekyll.git themes/jekyll
```

## Enable

Modify `theme` setting in `_config.yml` to `jekyll`:

```yaml
theme: jekyll
```

Add `feed` setting:

```yaml
feed:
  type: atom
  path: atom.xml
  limit: 20
```

## Add Demo.md

For better experience, you can remove default demo markdown file by using the follow command and add another markdown file provided by this theme:

```bash
$ rm source/_posts/hello-world.md && mv themes/jekyll/.post/demo.md source/_posts 
```

## Run

```bash
$ hexo g && hexo s
```

## Update

``` bash
$ cd themes/jekyll && git pull
```

## Contribute

- [Issue Tracker](https://github.com/pinggod/jekyll/issues)
- [Source Code](https://github.com/pinggod/jekyll)

## Support

If you are having issues, please let me know.
**MIALTO**: pinggodstudio[at]gmail.com

## License

MIT
