# usbreset
Tiny utility to reset a USB controller on linux.

## Usage
`usbreset device-filename (/dev/bus/usb/xxx/xxx)`

For example:

lsusb shows `Bus 003 Device 007: ID 1c75:af80 Arturia MiniFuse 1`

Reset via `./usbreset 003/007`

### TODO
* makefile
