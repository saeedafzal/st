# st - simple terminal
st is a simple terminal emulator for X which sucks less.

## Requirements
In order to build st you need the Xlib header files.

## Installation
Edit config.mk to match your local setup.

Afterwards enter the following command to build and install st:

```
make clean install
```

## Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```
tic -sx st.info
```

See the man page for additional details.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

## Fork
Custom changes:
* Custom install location
* Custom zoom keys (`ctrl+shift+plus`/`ctrl+shift+minus`)

Patches applied:
* [Alpha](https://st.suckless.org/patches/alpha)
