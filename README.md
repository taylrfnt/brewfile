# brewfile

## What is this repo?
This repo is really only useful for systems where you cannot install Nix (package manager) to use the [dotfiles repo](https://github.com/taylrfnt/dotfiles).

Homebrew has a concept of bundles, which allow you to declaratively install casks, taps, and formulae.  This repo is just that - a simple `Brewfile` to pass to the Homebrew `bundle` module.

## Using this Repo
All you need to do is [install Homebrew](https://brew.sh) and git.  

Clone this repo down to your local:
```bash
git clone https://github.com/taylrfnt/brewfile
```

Then run the following Homebrew command (making sure the `Brewfile` is in your current working directory)
```bash
cd brewfile && brew bundle
```

Homebrew will install all the casks, taps, and formulae you have specified in the Brewfile.
