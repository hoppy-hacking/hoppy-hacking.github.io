# hoppy-hacking.github.io

*this is a note to the maintainer*
```shell
# prerequisites: npm

# installation
$ npm install hexo-cli -g
$ cd /path/to/hoppy-hacking.github.io/  # NOT the GitHub.com repo!
$ npm install

# usage
# deployment one-liner
$ hexo clean && hexo generate && cp README.md public/ && cp index.html public/ && hexo deploy
```
