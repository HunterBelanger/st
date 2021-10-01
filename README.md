# Hunter's st Rice

This is my personal rice of st-0.8.4.

## Patches

The patches which have already been applied to this st rice are:

* st-alpha-0.8.2.diff
* st-scrollback-0.8.4.diff
* st-scrollback-mouse-20191024-a2c479c.diff
* st-scrollback-mouse-altscreen-20200416-5703aa0.diff
* st-ligatures-alpha-scrollback-20210824-0.8.4.diff

## Install
Before compiling, be sure to change the font and font size to a desirable
setting for your system. The default font will be quite large on non
HiDPI screens! Because the ligatures patch has been applied, the HarfBuzz
library is now required to build st.

Run `# make clean install` to build and install to your system. If not using
the `make install` command, compile st with `$ tic -sx st.info` to ensure the
terminfo entry is also compiled.
