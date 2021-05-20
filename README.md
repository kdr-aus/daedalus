# daedalus

Daedalus is a data _rendering_ and data _manipulation_ tool enabling **powerful**, **insightful**, and **fast** reporting.

Check it out at https://daedalus.report

## Installation

To install `daedalus`, it is recommended to follow the [INSTALLATION.md](./INSTALLATION.md) document.

# Installation

## Requirements
`daedalus` does not require any dependencies to run, however for an optimal experience
using `daedalus`, it is recommended that:
1. A high quality text editor is installed. `daedalus` has support for [`vscode`].
2. [Firefox] or [Google Chrome] is used as the rendering browser.

## Getting started
First download the `zip` file of the [latest
release](https://github.com/kdr-aus/daedalus/releases). It is recommended to use a
`stable` release. Extract the contents of the archive and run the executeable
`daedalus-bin.exe`. If Windows Smart Screen is enabled you may be blocked from executing
the file. Please contact your system administrator to allow you to run the software.
Once `daedalus` is running, please refer to [the Book](https://kdr-aus.github.io/daedalus/) for usage guides.

## Optional Features
`daedalus` has an optional REPL which can be used to extend and augment the base
functionality.
Learning to use the features can greatly enhance `daedalus`' feature set. To enable the
optional features, an installation of [`rust`] is required, along with a dependency for Microsoft's
[Visual C++ Build Tools.][build-tools]

### Microsoft Visual C++ Build Tools
`rust` requires Microsoft Visual C++ Build Tools for Windows. **The build tools need to be installed before installation of `rust`.** The tooling can be [downloaded
here][build-tools].
**Please include the Windows 10 SDK as part of the installation**. For more information see [here](https://www.rust-lang.org/tools/install).

[build-tools]: https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019
[`vscode`]: https://code.visualstudio.com/
[Firefox]: https://www.mozilla.org/en-US/firefox/new/
[Google Chrome]: https://www.google.com/chrome/
[`rust`]: https://www.rust-lang.org/
