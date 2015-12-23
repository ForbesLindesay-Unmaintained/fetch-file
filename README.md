# Fetch File

Download from an http server to a local file.

[![Build Status](https://img.shields.io/travis/ForbesLindesay/fetch-file/master.svg)](https://travis-ci.org/ForbesLindesay/fetch-file)
[![Dependency Status](https://img.shields.io/david/ForbesLindesay/fetch-file.svg)](https://david-dm.org/ForbesLindesay/fetch-file)

## Installation

    $ npm install fetch-file

## API

### fetch(remote, local, [options,] cb)

Download from `remote` to `local`.

`remote` is an options object to be passed to [request](https://github.com/mikeal/request#requestoptions-callback).  This includes `uri`, `qs`, `method`, `headers` etc...

`local` is the path to a local file.  Its directory will be created using mkdirp if it does not already exist.

Options:

 - `mode` The mode to create files with (default: 0666)

## License

BSD
