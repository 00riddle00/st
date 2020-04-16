## My build of st - the simple (suckless) terminal

The [suckless terminal (st)](https://st.suckless.org/) with some additional features.

### Notes on Emojis and Special Characters

If st crashes when viewing emojis, install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR.

Note that some special characters may appear truncated if too wide. One might want to manually set the prefered emoji/special character font to a lower size in the `config.h` file to avoid this. By default, JoyPixels is used at a smaller size than the usual text.
