# ScholarMacs

## LizardDude's Emacs config for humanities students and academics! 
![Philosophical GNU](https://www.gnu.org/graphics/philosophical-gnu-sm.jpg)

Copyright © 1997 Markus Gerwinski

## What does the config do?

This configuration file uses a variety of packages including orderless, vertico, marginalia, and Ebib with more packages to come in order to set up a powerful, integrated environment for students and academics. Also included are a slew of QOL and visual tweaks to Emacs' built-in functionality and packages (including org-mode and the modus themes). Emacs can replace the feature sets of many proprietary applications, but it can look good while doing it! Try it out!

## How do I install it?

Just copy and paste sections of this file (or even the entire file!) into your config file :D Remember to replace all PLACEHOLDER values (e.g. for your .bib and .csl files). Additionally, you may wish to adjust the fonts to your liking. Open Sans and DejaVu Sans Serif fonts are used—check that they're installed on your system.

Also, check that the MELPA archive is configured; you can do that by adding the following to the top of your config file:

```
(require 'package)
(add-to-list 'package-archives '("melpa" . "https://melpa.org/packages/") t)
;; Comment/uncomment this line to enable MELPA Stable if desired.  See `package-archive-priorities`
;; and `package-pinned-packages`. Most users will not need or want to do this.
;;(add-to-list 'package-archives '("melpa-stable" . "https://stable.melpa.org/packages/") t)
(package-initialize)
```

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
