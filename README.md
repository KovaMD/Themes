# Kova Themes

Community and official theme packs for [Kova](https://github.com/KovaMD/Kova).

## Installation

1. Copy any `.yaml` file into your Kova themes folder:
   - **Linux / macOS:** `~/.kova/themes/`
   - **Windows:** `%APPDATA%\kova\themes\`
2. Restart Kova.
3. The theme will appear in the theme picker (toolbar or Settings → Themes).

## Theme Packs

### EKC — East Kent Colleges Group (`ekc/`)

Campus themes for East Kent Colleges Group, built around each campus brand colour.

| File | Campus | Brand Colour |
|---|---|---|
| `ekc-group.yaml` | EKC Group | Teal `#00B6AE` |
| `ekc-ashford.yaml` | Ashford | Navy `#144C99` |
| `ekc-broadstairs.yaml` | Broadstairs | Magenta `#BD409C` |
| `ekc-canterbury.yaml` | Canterbury | Sky Blue `#00A0E4` |
| `ekc-dover.yaml` | Dover | Green `#4FA938` |
| `ekc-folkestone.yaml` | Folkestone | Purple `#7669B1` |
| `ekc-sheppey.yaml` | Sheppey | Orange `#E37611` |

All EKC themes use Montserrat (falling back to Inter), left-aligned title slides, and a left accent bar decoration.

### Generic — Developer community themes (`generic/`)

Classic colour schemes widely used in editors and terminals, adapted for presentations.

| File | Theme | Style | Accent |
|---|---|---|---|
| `nord.yaml` | Nord | Dark | Frost blue `#88C0D0` |
| `one-dark.yaml` | One Dark | Dark | Blue `#61AFEF` |
| `gruvbox-dark.yaml` | Gruvbox Dark | Dark | Orange `#FE8019` |
| `gruvbox-light.yaml` | Gruvbox Light | Light | Orange `#A34800` |
| `dracula.yaml` | Dracula | Dark | Purple `#BD93F9` |
| `tokyo-night.yaml` | Tokyo Night | Dark | Blue `#7AA2F7` |
| `solarized-dark.yaml` | Solarized Dark | Dark | Blue `#268BD2` |
| `solarized-light.yaml` | Solarized Light | Light | Blue `#1B6CA8` |
| `catppuccin-mocha.yaml` | Catppuccin Mocha | Dark | Mauve `#CBA6F7` |
| `catppuccin-latte.yaml` | Catppuccin Latte | Light | Mauve `#8839EF` |
| `monokai.yaml` | Monokai | Dark | Green `#A6E22E` |
| `big-blue.yaml` | Big Blue | Light | IBM Blue `#0f62fe` |

All generic themes use Inter (or IBM Plex Sans where noted) (falling back to Helvetica Neue / Arial), left-aligned title slides, and a left accent bar decoration. Colour values are sourced from the canonical upstream palettes; primary tones are darkened where necessary to meet WCAG AA contrast with white title text.

## Contributing

Themes are plain YAML files. Copy `example.yaml` from your Kova themes folder as a starting point, then open a PR.
