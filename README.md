> [!WARNING] 
> Archived in favor of [Dark Pastel](https://github.com/chaptergy/homeassistant-theme-grey-pastel), which is very similar but with more pastel colors. Because I also changed the accent color to a light orange, I did not want to release it as an update but instead as a new theme.

## Noctis Grey

Dark Grey Theme with Blue accent Colors for [Home Assistant](https://www.home-assistant.io).  
Based on [Noctis by aFFekopp](https://github.com/aFFekopp/noctis).

[![Donate on Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/chaptergy/donate)
<a href="https://www.buymeacoffee.com/chaptergy" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Donate on Buy Me A Coffee" height="30" width="127"></a>

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
