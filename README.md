# Dotfiles
This is a place to keep config files and other things that have to be set up, for example on a new computer.

`./script/make-symlinks` creates symlinks from the paths under dotfiles.

Here's the file structure for the repo:
`dotfiles/human-readable-tag/maybe-directory/something.symlink/more-stuff`

- Everything after the human-readable-tag is symlinked, and the first bit gets a dot added to it.
- something.symlink becomes /usr/local/bin/.something
- In this example, more-stuff is some kind of config file under ~/.maybe-directory/something/ and it's in our repo. The symlink means it's also where it's supposed to be.

(Execept `dotfiles/bin`. That's supposed to be code I guess? Mine's empty *shrug*) 
