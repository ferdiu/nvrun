# nvrun
`nvrun` is a simple script that aims to make life easier for people who want to be able to switch easly between bumblebee and nvidia-xrun.

## Usage:
Simply replace all `optirun` and `primusrun` occurences in your scripts and .desktop files with `nvrun`.

From terminal to launch a program run:
```
$ nvrun COMMAND
```

## Structure

* **nvrun** - uses following dir structure:
* **/usr/bin/nvrun** - the executable script
* **/etc/default/nvrun** - the main confing file
* **[OPTIONAL] /usr/share/bash-completion/completions/nvrun** - the bash-completion file

## DEB Package
The Debian package (not tested in Ubuntu and derivates) can be found [here](https://ferdiu.github.io/debs/nvrun_0.1-1.deb).
