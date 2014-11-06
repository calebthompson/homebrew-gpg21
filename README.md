# homebrew-gpg21

This repository contains a [Homebrew][brew] formula for [GnuPG 2.1](https://gnupg.org/faq/whats-new-in-2.1.html),
just for testing until that version of GPG lands in Homebrew proper

**You will need to [install Homebrew][brew_install] to use this**, see
[here][brew_install].

[brew]: http://mxcl.github.com/homebrew/
[brew_install]: https://github.com/mxcl/homebrew/wiki/installation

## Usage

There are two methods to install packages from this repository.

### Method 1: Tap

Tap the repository into your brew installation

```
brew tap mtigas/gpg21
```

And you can then install the forumla by doing:

```
brew install -vd mtigas/gpg21/gnupg21

#or

brew install -vd gnupg21
```


### Method 2: Raw URL

You can install the formula without tapping this repo by doing:

```
brew install -vd https://github.com/mtigas/homebrew-gpg21/raw/master/Formula/gnupg21.rb
```
