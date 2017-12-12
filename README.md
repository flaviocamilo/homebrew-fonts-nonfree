# Non-Free Fonts

This [Homebrew](http://brew.sh)/[Caskroom](http://caskroom.io) tap contains non-free fonts from around the Internet.

## License and copyright

Note that no font files or archives are kept in this repository. This repository makes it easier to install the font files from well-known locations.

Assume that each font is copyrighted, but permitted to be used provided that you have installed a certain program or otherwise paid a certain party for its use.

If you use a commercial font in a commercial work and you didn't pay for the font or otherwise gain permission to use it, the ghost of [Morris Fuller Benton](https://en.wikipedia.org/wiki/Morris_Fuller_Benton) will mess with your kernings now and forevermore.

All casks (in `Casks`) are in the public domain, or [CC0] where public domain doesn't exist.

[CC0]: https://creativecommons.org/publicdomain/zero/1.0/

## How to get these fonts

Firstly, if you don't have [Homebrew](http://brew.sh), install it:

	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Then tap [Cask](http://caskroom.io)'s repository:

	brew tap caskroom/cask

Then tap this repository:

	brew tap flaviocamilo/fonts-nonfree

And then install the fonts:

	brew cask install font-microsoft-office

## Notable inclusions

* The Microsoft Office 2007 fonts in `font-microsoft-office`
	* Owners of some Microsoft products may use. Se `brew cask info font-microsoft-office` for known caveats.
	* Included fonts:
		* Calibri
		* Cambria
		* Candara
		* Consolas
		* Constantia
		* Corbel
