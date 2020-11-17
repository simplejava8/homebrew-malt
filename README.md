# 🍺 Malt

> Are you a Windows user? Check out my [Scoop](https://scoop-docs.now.sh/) bucket [**Sushi**](https://github.com/kidonng/sushi).

A flavored [Homebrew](https://brew.sh/) tap, providing various kinds of applications.

Spot an error? Find a place which can be improved? Or your favorite application isn't included? Feel free to [submit an issue](https://github.com/kidonng/homebrew-malt/issues/new) or make a pull request!

**NOTE**: Unlike official taps, some formulae are updated automatically via GitHub Actions to reduce maintenance burden, which *may* cause installation issues.

## Usage

```sh
brew tap kidonng/malt
brew install <formula>
# Or just
brew install kidonng/malt/<formula>
```

## Formulae

The lists are sorted alphabetically.

`#` Require root permissions (`sudo`)

<details>
<summary><strong>Hackintosh</strong></summary>

Including most tools used in [Dortania Guides](https://dortania.github.io/).

- [gensmbios](https://github.com/corpnewt/GenSMBIOS)
- [gfxutil](https://github.com/acidanthera/gfxutil)
- [ifrextract](https://github.com/LongSoft/Universal-IFR-Extractor)
- [ioregistryexplorer](https://github.com/khronokernel/IORegistryClone)
- [opencore-utils](https://github.com/acidanthera/OpenCorePkg)
- [propertree](https://github.com/corpnewt/ProperTree)
- [uefitool](https://github.com/LongSoft/UEFITool)

</details>

<details>
<summary><strong>Fonts</strong></summary>

- [New York](https://developer.apple.com/fonts/) `#`
- [SF Compact](https://developer.apple.com/fonts/) `#`
- [SF Mono](https://developer.apple.com/fonts/) `#`
- [SF Pro](https://developer.apple.com/fonts/) `#`

</details>

<details>
<summary><strong><a href="https://qv2ray.net/">Qv2ray</a></strong></summary>

- [qv2ray-beta](qv2ray-beta)

</details>

<details>
<summary><strong>Misc</strong></summary>

- [neofetch-optional-deps](https://github.com/dylanaraps/neofetch.git)

  Install with `--without-imagemagick --without-screenresolution` to prevent pulling lots of dependencies.

- [unsign](https://github.com/steakknife/unsign)

  Useful for dealing with issues like [this](https://github.com/Nyx0uf/qlImageSize#limitations).

</details>
