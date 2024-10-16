# yarg
Yet another UNIX-like argument parser for C. CC0-licensed.

## Why another argument parsing library?

Four reasons:
- `yarg` is a header-only library, meaning that you can simply copy-and-paste it into project. It is also CC0-licensed, meaning that you can use it in just about any program without licensing obligations.
- `yarg` supports short and long options, Windows-style flags `/like-this` and short flag styles `-like -this=3`, not just the UNIX-y `-ab5 --like-this`.
- `yarg` actually parses the arguments and gives you a structure that is fundamentally independent of the contents of argv.
- `yarg` supports mixed positional arguments with flags, e.g. `--flag file_name.txt --flag2`.
