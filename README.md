# dotfiles-mini

A minimal dotfiles repository.

The `bootstrap` script iterates through all **topic** subdirectories (bash,
example and git) and runs `bootstrap` scripts found inside these directories.
These **topic**-specific bootstrappers then may install additional tools and
symlink files to their locations inside your `$HOME` directory (or somewhere
else).

The setup is quite minimal, e.g. symlinking does not create backups but also
does not overwrite existing files (it may print errors if a file already
exists).

This repository is intended as a starting point for your own dotfiles
repository. Alternatively, you may want to fork a dotfiles framework like
[`sds/dot`](https://github.com/sds/dot) and work from there or research the
[numerous public dotfiles
repositories](https://github.com/search?utf8=%E2%9C%93&q=dotfiles&type=) created
by other people.
