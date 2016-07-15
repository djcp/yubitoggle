# yubitoggle

Use xinput to toggle a yubikey on and off. This allows you to keep the key
plugged in and not worry about accidentally entering tokens with errant
touches.

## Getting started

- Clone this repo
- Install `xinput` through your package manager.
- Put `yubitoggle` somewhere on path. It doesn't require any special privileges.
- Run `yubitoggle` If all goes well, your yubikey will be enabled / disabled.
- You can run `DEBUG=1 yubitoggle` to get some basic debugging info.
- `yubitoggle --state` will tell you if the yubikey is off or on. "0" == off,
  "1" == on. This is useful in scripts.

## Known issues

- This only works for a single yubikey.
- Only tested on ubuntu 16.04 but should work on a bunch of linuxes.

## See also

- [yubiswitch for linux](https://github.com/gsstark/yubiswitch-for-linux)

## Contributors

- Dan Collis-Puro

## License

MIT
