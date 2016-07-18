# Enki Theme for Sublime Text
A dark color scheme and UI theme with clear, disparate colors to help differentiate between all syntactic aspects of code, including syntax highlighting for the console.

The UI theme itself is a **modified version** of
[equinusocio's](https://github.com/equinusocio) amazing work,
[Material Theme](https://github.com/equinusocio/material-theme) and
[Material Theme Appbar.](https://github.com/equinusocio/material-theme-appbar)
Specifically, the overall UI colors have been changed in Material App Bar and Material Theme to better align with this color scheme.

<a href="https://raw.githubusercontent.com/enkia/enki-theme/master/screenshots/screenshot1.png" target="_blank">
    <img src="screenshots/screenshot1.png" alt="Preview" width="890">
</a>

Alternate color scheme:

<a href="https://raw.githubusercontent.com/enkia/enki-theme/master/screenshots/screenshot2.png" target="_blank">
    <img src="screenshots/screenshot2.png" alt="Preview" width="890">
</a>


## Installation
1. Download the package

    **Preferred Method:** With [Package Control](https://packagecontrol.io/installation) installed, open the command palette and type `install package` and search for `Enki Theme.`

    *Alternate Method:* [Download](http://github.com/enkia/enki-theme/archive/master.zip) or clone this repo into `Sublime Text 3/Packages` and rename the folder to 'Enki Theme'

2. Open preferences and change the color scheme and theme lines:

```json
"color_scheme": "Packages/Enki Theme/scheme/Enki.tmTheme",
"theme": "Enki-Theme.sublime-theme",
```

For those who prefer something less purple:
```json
"color_scheme": "Packages/Enki Theme/scheme/Enki-Alt.tmTheme",
```

## Options
Because this is essentially Material Theme, it comes packed the [same options](https://github.com/equinusocio/material-theme#theme-options) as the original with the exception of contrast mode.
There are, however, *five more color options* that coordinate well with this color scheme and *one additional option:*

```json
  "enki_theme_color_expanded_folder": true, // Set Expanded Folder in Sidebar to the accent color.
                                            // If no accent color is specified, it simply gets brighter.

  "enki_theme_accent_samon": true,
  "enki_theme_accent_bluegray": true,
  "enki_theme_accent_fuschia": true,
  "enki_theme_accent_white": true,
  "enki_theme_accent_green": true,

  "enki_theme_accent_lime": true,
  "enki_theme_accent_purple": true,
  "enki_theme_accent_pink": true,
  "enki_theme_accent_red": true,
  "enki_theme_accent_orange": true,
  "enki_theme_accent_indigo": true,
  "enki_theme_accent_teal": true,
  "enki_theme_accent_blue": true,
  "enki_theme_accent_cyan": true,
  "enki_theme_accent_yellow": true,
```

Options to mimic the screenshot:

```json
  "enki_theme_accent_samon": true, // accent color samon
  "enki_theme_compact_sidebar": true,
  "enki_theme_contrast_mode": true,
  "enki_theme_panel_separator": true,
  "enki_theme_small_statusbar": true,
  "enki_theme_small_tab": true,
  "enki_theme_tabs_autowidth": true,
  "enki_theme_tree_headings": false,

  "bold_folder_labels": false,
  "always_show_minimap_viewport": true,
  "indent_guide_options": ["draw_normal", "draw_active"],
  "font_options": ["gray_antialias", "subpixel_antialias"], // for retina Mac & Windows
```

## Notes
* **Ruby developers:** Try removing Ruby Slim package if syntax appears muddled.
* **SCSS/SASS developers:** This theme is best used with the [SCSS - TextMate SCSS Official Bundle](https://packagecontrol.io/packages/SCSS) because the Sass package has fewer syntax definitions to work with.
* **Javascript developers:** This theme is best used with the [newly updated (see build 3114 notes)](https://www.sublimetext.com/3) default Javascript syntax definitions or the ones from the [Babel](https://packagecontrol.io/packages/Babel) package.
* **iTerm color preset** included!



## Issues / Requests / Contributions
#### Color Scheme:
* If a syntax definition doesn't appear to be supported, please let me know by [submitting an issue.](http://github.com/enkia/enki-theme/issues)
* Use the supplied YAML file for use with [PackageDev](https://packagecontrol.io/packages/PackageDev) if you'd like to contribute to the *color scheme.*

#### Theme:
Despite this being a modified version of the Material Theme, please submit UI issues here as I may have introduced a bug when changing the theme.

I will attempt to keep this updated with all major bug fixes released by
[equinusocio](https://github.com/equinusocio) for
[Material Theme](https://github.com/equinusocio/material-theme) and
[Material Theme Appbar](https://github.com/equinusocio/material-theme-appbar)
but understand that since I'm not the original developer of the UI theme, these updates will not occur immediately.
*Note:* There is **[a known issue](https://github.com/equinusocio/material-theme#known-issues)** that may affect some people.

