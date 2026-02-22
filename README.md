<a href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg" alt="License"></a>
<a href="https://www.gnu.org/software/emacs/download.html"><img src="https://raw.githubusercontent.com/emacs-eine/badges/main/elpa/emacs.svg" alt="Emacs"></a>
<a href="#"><img src="https://raw.githubusercontent.com/emacs-eine/badges/main/elpa/packages.svg" alt="Packages"></a>
<a href="#"><img src="https://raw.githubusercontent.com/emacs-eine/badges/main/elpa/system.svg" alt="System"></a>

<img align="right" width="20%" src="./docs/etc/logo.png">

# EINE Elpa
> ELPA for [EINE][], using [github-elpa](https://github.com/10sr/github-elpa)

Here are the goals for this [ELPA][]:

- Host all EINE packages for public use.

## 🔨 How to use?

Add the following to your configuration:

```elisp
(add-to-list 'package-archives '( "eine" . "https://emacs-eine.github.io/elpa/packages/") t)
```

Use priority if you don't want this archive overridden with other larger archives:

```elisp
(setq package-archive-priorities '(("gnu"   . 5)
                                   ("melpa" . 5)
                                   ("eine"  . 0)))
```

## 🛠️ Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either clone and make pull
requests to this repository. Or you can clone the project and establish your own
branch of this tool. Any methods are welcome!

## ⚜️ License

This work is licensed under the [CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/) license.

[![](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nd/4.0/)
[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

[![Build](https://github.com/emacs-eine/elpa/actions/workflows/build.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/build.yml)
[![Archive](https://github.com/emacs-eine/elpa/actions/workflows/archive.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/archive.yml)
[![Install](https://github.com/emacs-eine/elpa/actions/workflows/install.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/install.yml)
[![System](https://github.com/emacs-eine/elpa/actions/workflows/system.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/system.yml)
[![Version](https://github.com/emacs-eine/elpa/actions/workflows/version.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/version.yml)
[![Packages](https://github.com/emacs-eine/elpa/actions/workflows/packages.yml/badge.svg)](https://github.com/emacs-eine/elpa/actions/workflows/packages.yml)


<!-- Links -->

[ELPA]: https://wikemacs.org/wiki/ELPA

[EINE]: https://github.com/emacs-eine
[github-elpa]: https://github.com/10sr/github-elpa
