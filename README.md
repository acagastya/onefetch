<h3 align="center"><img src="assets/onefetch.svg" height="130px"></h3>

<h5 align="center">A command-line Git information tool written in Rust</h5>

<p align="center">
	<a href="https://crates.io/crates/onefetch"><img src="https://img.shields.io/crates/v/onefetch.svg" alt="cargo"></a>
	<a href="https://github.com/o2sh/onefetch/actions"><img src="https://github.com/o2sh/onefetch/workflows/CI/badge.svg" alt="Build Status"></a>
	<a href="https://github.com/o2sh/onefetch/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22"><img src="https://img.shields.io/github/issues/o2sh/onefetch/help%20wanted?color=green" alt="help wanted"></a>
	<a href="./LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</p>

<p align="center">
  <a href="https://snapcraft.io/onefetch"><img src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" alt="Get it from the Snap Store"></a>
</p>

<img src="assets/react.png" align="right" height="240px">

Onefetch is a command-line Git information tool written in `Rust` that will display project information and code statistics about your Git repository directly on your terminal.

By default, the repo's information is displayed alongside the dominant language's ASCII logo, but you can further configure Onefetch to instead display an image - on supported terminals (more info [here](https://github.com/o2sh/onefetch/wiki/Images-in-the-terminal)) -, a text input or nothing at all.

It automatically detects open source licenses from texts and provides the user with various information like code distribution, pending changes, dependencies, top contributors (by number of commits), size on disk, creation date, version, HEAD, last change, LOC (lines of code), etc.

<img src="assets/kubernetes.png" align="right" height="240px">

Onefetch can be configured via command-line flags to display exactly what you want, the you want it to: you can customize ASCII/Text formatting, disable info lines, ignore files & directories, etc; read more about it [here](https://github.com/o2sh/onefetch/wiki/command-line-options).

As of now, onefetch supports more than 50 different programming languages; if your language of choice isn't supported: Open up an issue and support will be added. 

Contributions are very welcome! See [CONTRIBUTING](https://github.com/o2sh/onefetch/blob/master/CONTRIBUTING.md) for more info.

### More: \[[Wiki](https://github.com/o2sh/onefetch/wiki)\] \[[Installation](https://github.com/o2sh/onefetch/wiki/Installation)\] \[[Getting Started](https://github.com/o2sh/onefetch/wiki/getting-started)\]
