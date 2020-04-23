<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-terminator/develop/src/assets/nord-terminator-banner.svg"/></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-terminator/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-terminator.svg?style=flat-square"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://gnometerminator.blogspot.de/p/introduction.html">Terminator</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-terminator/develop/src/assets/scrot-colortest.png"/><blockquote>Font: <a href="https://adobe-fonts.github.io/source-code-pro">Source Code Pro</a> 12px.</blockquote></p>

## Installation

To install _Nord_, the content of the [`config`][src-config] file must be manually transferred to [your configuration file][archw-terminator#config] that is usually located at `~/.config/terminator/config`.

1. Replace or add the configuration keys for the `global_config` section:
   ```diff
   [global_config]
   +  title_inactive_bg_color = "#4C566A"
   +  title_inactive_fg_color = "#D8DEE9"
   +  title_receive_bg_color = "#8FBCBB"
   +  title_receive_fg_color = "#2E3440"
   +  title_transmit_bg_color = "#88C0D0"
   +  title_transmit_fg_color = "#2E3440"
   ```
2. Append the `[[nord]]` profile of to the `[profiles]` section to create a new profile for _Nord_:
   ```diff
   [profiles]
   +  [[nord]]
   +    background_color = "#2E3440"
   +    cursor_color = "#D8DEE9"
   +    foreground_color = "#D8DEE9"
   +    palette =    "#3B4252:#BF616A:#A3BE8C:#EBCB8B:#81A1C1:#B48EAD:#88C0D0:#E5E9F0:#4C566A:#BF616A:#A3BE8C:#EBCB8B:#81A1C1:#B48EAD:#8F  BCBB:#ECEFF4"
   ```

## Screenshots

<p align="center"><strong>htop</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-terminator/develop/src/assets/scrot-htop.png"/></p>

## Development

[![](https://img.shields.io/badge/Changelog-0.1.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-terminator/blob/v0.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution

Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-terminator/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center">Copyright &copy; 2016-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-terminator/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>

[archw-terminator#config]: https://wiki.archlinux.org/index.php/Terminator#Configuration
[src-config]: https://github.com/arcticicestudio/nord-terminator/blob/develop/src/config
