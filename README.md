# fast-cli
[![Travis CI](https://img.shields.io/travis/xv-geoff-hb/fast-cli/master.svg?style=flat-square)](https://travis-ci.org/xv-geoff-hb/fast-cli)
[![Software License](https://img.shields.io/badge/License-MIT-orange.svg?style=flat-square)](https://github.com/xv-geoff-hb/fast-cli/blob/master/LICENSE)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square)](https://godoc.org/github.com/xv-geoff-hb/fast-cli)

fast-cli estimates your current internet download speed by performing a series of downloads from Netflix's fast.com servers.


## Installing

### Compile
This project requires go 1.6+ to compile. Just run `go get -u github.com/xv-geoff-hb/fast-cli` and the executable should be built for you automatically in your `$GOPATH`.

Optionally you can run `make install` to build and copy the executable to `/usr/local/bin/` with correct permissions.

### Download
Once you have an executable, make sure to copy it somewhere on your path like `/usr/local/bin` or `C:/Program Files/`.
If on a \*nix/mac system, make sure to run `chmod +x /path/to/fast-cli`.

## Usage

```console
fast-cli estimates your current internet download speed by performing a series of downloads from Netflix's fast.com servers.

Usage:
  fast-cli [flags]

Flags:
  -h, --help       help for fast-cli
  -n, --no-https   Do not use HTTPS when connecting
  -s, --simple     Only display the result, no dynamic progress bar
      --version    Display the version number and exit
  -p, --proxy      Execute test through an HTTP/HTTPS proxy
```
Optionally, a hidden debug flag is available in case you need additional output.
```console
Hidden Flags:
  -D, --debug                  Include debug statements in log output
```

## Documentation

This documentation can be found at github.com/xv-geoff-hb/fast-cli

## License

This package is made available under an MIT-style license. See LICENSE.

## Contributing

PRs are always welcome!
