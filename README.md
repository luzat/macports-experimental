# Thomas Luzat's experimental MacPorts

This repository contains some of my experimental MacPorts. Feel free to use them, but they may not work as expected.

## Getting started

1. Make sure that [MacPorts](https://www.macports.org/) are installed.
2. `cd` to some directory which is accessible by `port` and where the repository will live.
3. Clone the repository: `git clone https://github.com/luzat/macports-experimental.git`
4. `cd macports-experimental && portindex`
5. Prepend `sources.conf` (most likely `/opt/local/etc/macports/sources.conf`) with `file:///$PWD/macports-experimental [nosync]`
6. Install some new port: `sudo port install fuse-ext2` 

## Updating the repository

1. `cd` to `macports-experimental`
2. `git pull && portindex`
3. Profit!

## Bug Reports / Contributing

Feel free to submit [tickets](https://github.com/luzat/macports-experimental/issues) or pull requests.

## License

The project is licensed under the BSD 2-Clause License. See the [LICENSE](LICENSE) file for details.
