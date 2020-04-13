# Common commands:

## apt
The `apt` command can be used to install different packages from web and official repositories. The command has to be used with `sudo` if you are installing or removing packages.\
Examples:
- `apt update` - This command can be used to fetch info about new packages from the apt-repositories.
- `apt upgrade` - This command should be used right after `apt update` and what it does, is installing the new updates to your packages.
- `apt install <packageName>` - This command is used to install new packages into the system. For example, if you wanted to install `neofetch`, what you would do is `sudo apt install neofetch`. That will automatically set up the package and be used right after the installation finishes.
- `apt remove <installedPackageName>` - This command uninstalls a package, that has been previously installed into the system. Self-explanatory.

## tar
The `tar` command is used to extract or pack the `*.tar` archives. Can be used with many `.tar` type packages, for example several of them are:
- `*.tar`
- `*.tar.gz`
- `*.tar.xz`

and many others...\
Examples:
- `tar -x path/to/archive.tar` - this command unpacks the archive in the current folder.

- `tar -x path/to/archive.tar -C path/to/unpack/dir` - this command unpacks the archive in the given directory.
