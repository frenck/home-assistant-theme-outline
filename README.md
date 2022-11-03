# Home Assistant Theme: Outline-Edge

This is a fork of the "depricated" Outline Theme provided by @frenck (https://github.com/frenck/home-assistant-theme-outline)

While the original Theme has just removed the default shadow from the HomeAssistant Cards, this package does provide a few more options:

1. "Default Home-Assistant Pre-2022.11.0 Theme"
With the Release of Home-Assistant 2022.11.0, the default Theme has increased Border-Radius and no shadows anymore.  
Therefore, this package does include a Theme that recreates the default style from Homeassistant.  
![grafik](https://user-images.githubusercontent.com/26391061/199812201-69697d52-1d70-4576-803d-020295908201.png)

2. "Original Outline-Theme"
Furthermore, for those who liked the default Outline-Theme (default border-radius, but no shadows), a recreation of the Outline Theme is available  
![grafik](https://user-images.githubusercontent.com/26391061/199812458-bfaa0721-1f57-45ff-a841-5f7d807fefcd.png)

3. "No Radius, but Shadows"
If you don't want any Border-Radius, but you do like the Shadow on the Cards from the default, theme, there's also an option available:  
![grafik](https://user-images.githubusercontent.com/26391061/199812679-88fee8e7-ad79-4c7f-a160-12a09e988632.png)

4. "No Radius, no Shadows"
And finally, the reason why I created this theme (personally) - no Border-Radius, and no shadows...  
![grafik](https://user-images.githubusercontent.com/26391061/199812894-a15ca444-8675-499c-8bab-9e43fdb983de.png)

All 4 options do support Light & Dark mode - just as the original Outline-Theme did.  
Unfortunately, the shadows in the Dark mode aren't really visible (yet)... that's something I probably will change soon :)  


## Installation

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### Manual Installation

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/ChristophCaina/home-assistant-theme-outline-edge
```

## Changelog & Releases

This repository keeps a change log using [GitHub's releases][releases]
functionality.

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

- `MAJOR`: Incompatible or major changes.
- `MINOR`: Backwards-compatible new features and enhancements.
- `PATCH`: Backwards-compatible bugfixes and package updates.

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We've set up a separate document for our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original setup of this repository is by [Franck Nijhof][frenck].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## License

MIT License

Copyright (c) 2021-2022 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
