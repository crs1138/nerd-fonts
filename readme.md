# Nerd Fonts

**Nerd Fonts** is a project that patches developer targeted fonts with a high number of

## Table of Contents

[**TLDR**](#tldr)

[**Installation Options**](#font-installation)
  * [**1 - Manual**](#option-1-download-and-install-manually)
  * [**2 - Install Script**](#option-2-install-script)

**Additional Info**
  * [**License**](#license)

### TL;DR

* Pick your font family and then select from the `'complete'` directory.
  * If you are on Windows pick a font with the `'Windows Compatible'` suffix.
    * This includes specific tweaks to ensure the font works on Windows, in particular monospace identification and font name length limitations
  * If you are limited to monospaced fonts (because of your terminal, etc) then pick a font with the `'Mono'` suffix.
    * This denotes that the Nerd Font glyphs will be monospaced not necessarily that the entire font will be monospaced

### Ligatures

By the *Nerd Font* policy, the variant with the `'Mono'` suffix is not supposed to have any ligatures.
Use the non-*Mono* variants to have ligatures.
### Various Download Options for Fonts

_If you..._

  * `Option 1.` want to **quickly** grab an **individual font** download from the [`patched-fonts/` directory](#patched-fonts)
  * `Option 2.` want to **automate** installing or use in **scripts** see the [Install Script](#option-2-install-script)

## Font Installation

### `Option 1: Download and Install Manually`

> Best option for **quickly** getting a specific **individual font**.

Download the specific [patched font](#patched-fonts) of your choice

### `Option 2: Install Script`

> Best option if you want to **automate** installing or for use in **scripts**.

_Note_: Only for Linux & macOS (OS X)
_Note_: **Requires cloning** the repo as of now

#### All fonts:

* Installs all the patched Fonts (_Warning: This is a lot of Fonts adding up to a large size_)

```sh
./install.sh
```

#### Single font:

* Installs a single Font of your choice

```sh
./install.sh <FontName>
./install.sh Hack
./install.sh HeavyData
```
## License

[MIT](LICENSE) © Ryan L McIntyre

