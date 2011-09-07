# Homebrew Formula for Alloy's MacVim

This is for [the split-browser branch of alloy/macvim](https://github.com/alloy/macvim).

# Installing

1.  Clone this repo
2.  Replace `/usr/local/Library/Formula/macvim.rb` or
    `~/Developer/Library/Formula/macvim.rb` with `macvim.rb` from this
    repo
3.  Uninstall macvim (`brew uninstall macvim`)
4.  Install macvim (`brew install macvim`)

# Uninstalling

1.  switch to the directory containing your Homebrew Formulas
2.  run `git checkout macvim.rb` to revert to the original file
3.  Uninstall and install macvim (steps 3 and 4 above)

# Keeping it

1.  switch to the directory containing your Homebrew Formulas
2.  add and commit the changes to your formula
3.  when you run brew update, if macvim.rb changes,  you'll need to merge it

# License

Same as Homebrew.

# FAQ

## Why not a Homebrew fork?

So you can just download the file that you need, without merging.

## Why not a gist?

So I can link to it by name.
