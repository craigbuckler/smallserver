# smallserver

[**GitHub**](https://github.com/craigbuckler/smallserver) | [**npm**](https://www.npmjs.com/package/smallserver) | [**donate**](https://gum.co/smallserver) | [@craigbuckler](https://twitter.com/craigbuckler) | [craigbuckler.com](https://craigbuckler.com/)

A small and fast cross-platform Node.js static file server with no dependencies. The directory default is `index.html` and correct MIME types are used.

Ideal for serving client-side code on a development machine, but not optimised for production servers (no compression, caching, etc.)


## Usage

Install globally:

```bash
npm i smallserver -g
```

Launch using `ss` or `smallserver` to serve files from the current root directory, e.g. <http://localhost:8888/>

To quit, press `Ctrl|Cmd + C`.


## Command line options

```bash
smallserver [port] [dir]
```

where:

* `[port]` is an optional HTTP port (8888 by default)
* `[dir]` is an optional absolute or relative root file directory (the current directory by default)


## Possible future features

* directory file list and navigation
* proxy to other servers


## Version history

### v1.0.0, 3 August 2019

* initial release
