# My Site

## Preview locally

```bash
$ hugo server --theme=hugo_theme_robust --buildDrafts
```
Go to http://localhost:1313/

## How to deploy
```bash
$ cd haibin
$ hugo --theme=hugo_theme_robust
$ cp -r public/ ../haibin.github.io

$ cd ../haibin.github.io
$ git add *
$ git commit -m "Update"
$ git push origin master
```