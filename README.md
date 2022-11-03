# Home Assistant Theme: Outline-Edge

[![Support Frenck on Patreon][patreon-shield]][patreon]

This Theme is a fork of Frenck's "Outline" theme, which will become depricated since the changes he made  
became now the default Theme of HomeAssistant.

Due to many replies in the Blog-Post of Home-Assistant (according the round edges on the card),  
I've decided to create this variation where the round edges have been removed completely.

Every thing else should still be like the default theme from HomeAssistant, because it is still mainly based on the theme from Frenck.


A Home Assistant Theme that makes all border more modern, minimalistic and
tight in both dark & light modes.

## About

This is probably the most minimalistic theme out there (in terms of what
it actually does and changes).

It respects almost all design choices and colors from Home Assistant, except
one... the border/layering of the cards.

This theme makes everything just a little tiny bit more modern, consistent,
and tight.

Nothing special, but if you just like the default Home Assistant theme, this
might be a small variation that you might like.

[![Home Assistant Theme: Outline; Before & After][preview]][preview]

This theme support both dark & light modes in a single theme.

## Installation

Add the following code to your `configuration.yaml` file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Outline`.
3. Navigate to `Outline` theme.
4. Press `Install`.
5. You are awesome!

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/frenck/home-assistant-theme-outline
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

[build-shield]: https://github.com/frenck/home-assistant-theme-outline/actions/workflows/linting.yaml/badge.svg
[build]: https://github.com/frenck/home-assistant-theme-outline/actions/workflows/linting.yaml
[contributors]: https://github.com/frenck/home-assistant-theme-outline/graphs/contributors
[frenck]: https://github.com/frenck
[github-sponsors-shield]: https://frenck.dev/wp-content/uploads/2019/12/github_sponsor.png
[github-sponsors]: https://github.com/sponsors/frenck
[license-shield]: https://img.shields.io/github/license/frenck/home-assistant-theme-outline.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[patreon-shield]: https://frenck.dev/wp-content/uploads/2019/12/patreon.png
[patreon]: https://www.patreon.com/frenck
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[releases-shield]: https://img.shields.io/github/release/frenck/home-assistant-theme-outline.svg
[releases]: https://github.com/frenck/home-assistant-theme-outline/releases
[semver]: http://semver.org/spec/v2.0.0.html
[preview]: https://github.com/frenck/home-assistant-theme-outline/raw/main/images/before-after.png
