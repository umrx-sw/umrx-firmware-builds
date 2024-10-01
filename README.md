# UMRX firmware builds

The repository stores the binary artifacts for the UMRX firmware:
* the `*.hex` Intel-HEX format,
* the `*.bin` binary format.

Each pipeline run creates a release with the `*.hex` and `*.bin` files.

## Release structure

* `umrx_for_app_v30_v${VERSION}.hex` firmware in Intel-HEX format;
* `umrx_for_app_v30_v${VERSION}.bin` firmware in binary format.

## Compatible hardware

The UMRX firmware is compatible with [Bosch Application Board 3.0](https://www.bosch-sensortec.com/software-tools/tools/application-board-3-0/).

## Download artifacts

Go to the [**Releases**](https://github.com/umrx-sw/umrx-firmware-builds/releases) page
of the repository and download `*.hex` and/or `*.bin` file for the corresponding release.


## Maintainer

[selyunin](https://github.com/selyunin)
