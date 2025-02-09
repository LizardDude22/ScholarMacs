# ScholarMacs

## LizardDude's Emacs config for humanities students and academics! 
![Philosophical GNU](https://www.gnu.org/graphics/philosophical-gnu-sm.jpg)

Copyright © 1997 Markus Gerwinski

## What does the config do?

This configuration file uses a variety of packages including orderless, vertico, marginalia, and Ebib (soon!) with more packages to come in order to set up a powerful, integrated environment for students and academics. Also included are a slew of QOL and visual tweaks to Emacs' built-in functionality and packages (including org-mode and the modus themes). Emacs can replace the feature sets of many proprietary applications, but it can look good while doing it! Try it out!

## How do I install it?

Just copy and paste sections of this file (or even the entire file!) into your config file :D Remember to replace all PLACEHOLDER values (e.g. for your .bib and .csl files). Additionally, you may need to adjust the fonts. Currently, Iosevka is used for non-variable pitch fonts. If you don't have the Iosevka font installed, it may cause an error. You can either install the Iosevka font or change it to another font of your choice. The same applies to Open Sans, though it's more likely to be pre-installed on your system. Also, check that the MELPA archive is configured.

## Is this it dude? Or are you planning on adding more?

There is lots to come! I plan on adding corfu and cape in order to improve citation insertion. I also plan to expand Ebib's functionality via some further configuration options, and add consult, embark and denote to the mix.


## Credits

This configuration installs and uses the following open-source packages in addition to Emacs' many built in packages:

- [Orderless](https://github.com/oantolin/orderless)
- [Vertico](https://github.com/minad/vertico)
- [Marginalia](https://github.com/minad/marginalia)
- [Ebib](https://github.com/joostkremers/ebib)

You can find more about these packages on their respective GitHub pages.

### Disclaimer

You should always audit third-party configs and packages when using Emacs. I’ve done my best to audit the packages used in this config, and I’ve tried to limit the config to the GNU ELPA archive as much as possible. However, some packages are taken from MELPA (currently only Ebib), and as such, they are subject to less oversight.

