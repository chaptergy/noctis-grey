## Noctis Grey

Dark Grey Theme with Blue accent Colors for [Home Assistant](https://www.home-assistant.io).  
Based on [Noctis by aFFekopp](https://github.com/aFFekopp/noctis).

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

## Screenshot

![](https://raw.githubusercontent.com/chaptergy/noctis-grey/master/img/screenshot1.jpg)

## Installation

<!-- #### HACS

1. Go to the Community Store.
2. Search for `Noctis Grey`.
3. Navigate to `Noctis Grey`.
4. Press Install. -->

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
