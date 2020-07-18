# Dotfiles
This is a place to keep config files and other things that have to be set up, for example on a new computer.

`./script/make-symlinks creates symlinks from the paths under dotfiles`

Everything starts at the user's home directory.
The basic structure goes like this:

dotfiles/human-readable-tag/maybe-directory/something.symlink/more-stuff

- Everything after the human-readable-tag is taken, and the first bit gets a dot added to it.
- The thing with the .symlink is the thing that gets a symlink generated. ~/.vimrc is symlinked to vimrc.symlink.
- In this example, more-stuff is some kind of config file under ~/.maybe-directory/something/ and it's in our repo. The symlink means it's also where it's supposed to be.
