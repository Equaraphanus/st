# suckless terminal

The [Luke's build of st](https://github.com/LukeSmithxyz/st) with some extra changes.

## Differences from upstream

- Font2 patch uses a single string with semicolon-separated list of values rather than an array of strings, which makes it possible to specify more than one fallback font in `.Xresources`
- The `.Xresources` entry used to get the fallback fonts is called `st.extraFonts`, not `st.fontalt0`
