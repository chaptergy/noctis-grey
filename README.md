## Noctis Grey

Dark Grey Theme with Blue accent Colors for [Home Assistant](https://www.home-assistant.io).  
Based on [Noctis by aFFekopp](https://github.com/aFFekopp/noctis).

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

## Screenshot

![](https://raw.githubusercontent.com/chaptergy/noctis-grey/master/img/screenshot1.png)

## Installation

#### HACS

1. Install the [Home Assistant Community Store](https://github.com/custom-components/hacs) if you do not have it already.
2. Go to the Community Store.
3. Click on the _Themes_ tab.
4. Search for _Noctis Grey_ and install it.
5. If this is the first theme you have installed though HACS, add the following to your configuration.yaml:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

#### Manual Installation

1. copy the `themes` folder into your home-assistant folder
2. add this to your `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. restart home-assistant
4. select the theme in your user's profile (bottom left)

**Optional**: I recommend installing [Custom Header](https://github.com/maykar/custom-header)
