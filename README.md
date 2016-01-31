# search

very simple tool to perform web searches from the terminal written in node. 
Inspired by [zquestz/s](https://github.com/zquestz/s) (and other cli apps) in 
functionality, but with a different implementation.

a small experimenting learning js and node (and just having fun).

# usage
```
  Usage: search [options] <query>

  Options:

    -h, --help                       output usage information
    -V, --version                    output the version number
    -s, --service <service>          to perform search on (e.g. google, npm)
    -c, --configure                  configure a new service
    -l, --list                       list configured services
```

# services
search-cli services are stored in a json configuration file placed in the user's
home directory during installation (at ~/.search-cli.json).

search-cli comes with some services already configured by default, but new 
services can be configured by:

1. running search-cli with the ``` --configure ``` flag.
1. manually editing the configuration file to add a new service.

# license
[MIT](https://github.com/latrokles/search-cli/blob/master/LICENSE)
