# Hunter's st Rice

This is my personal rice of the suckless simple terminal or st.  This is a patched version of st 0.8.2 with color alterations.

## Patches

The patches which have already been applied to this st rice are:

* st-alpha-0.8.2.diff
* st-rightclickpaste-0.8.2.diff
* st-scrollback-0.8.2.diff
* st-scrollback-mouse-0.8.2.diff
* st-scrollback-mouse-altscreen-201901310e23acb9.diff



## Install
Before compiling be sure to change the font and font size to a desirable setting for your system. The default font will be quite large on non HiDPI screens!

Run `# make clean install` to build and install to your system. If not using the `make install` command, compile st with `$ tic -sx st.info` to ensure the terminfo entry is also compiled.
