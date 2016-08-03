# My Site

## Preview locally

```bash
$ hugo server --theme=hugo-theme-bleak --buildDrafts
```
Go to http://localhost:1313/

## How to deploy
```bash
$ cd haibin
$ hugo --theme=hugo-theme-bleak
$ cp -r public/ ../haibin.github.io

$ cd ../haibin.github.io
$ git add *
$ git commit -m "Update"
$ git push origin master
```