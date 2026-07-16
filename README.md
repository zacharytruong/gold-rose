# Gold Rose

A warm, dark color scheme and UI theme for [Sublime Text](https://www.sublimetext.com/),
built around a muted gold, rose, and dusty-pink palette. Easy on the eyes for
long sessions, with just enough color variety to keep syntax readable.

## What's included

- **Gold Rose.sublime-color-scheme** — the syntax color scheme.
- **Gold Rose.sublime-theme** — a matching UI theme that warms the window chrome
  (tabs, sidebar, status bar) toward the same palette.

## Requirements

- Sublime Text 4 (build 4050+).

Nothing else. The theme extends `Adaptive.sublime-theme`, which ships with
Sublime Text, so both files work on a stock install.

### Optional: nicer file icons

Sublime ships seven generic file-type icons, so `.py`, `.rs` and `.go` all fall
into the same coarse "source" bucket. Installing
[`A File Icon`](https://packagecontrol.io/packages/A%20File%20Icon) gives every
language its own icon. It detects the active theme and patches itself in — no
configuration needed. Folder icons are built into Sublime and look the same
either way.

## Installation

### Package Control (recommended)

1. Open the Command Palette (`Cmd/Ctrl+Shift+P`).
2. Run **Package Control: Install Package**.
3. Search for **Gold Rose** and install it.

### Manual

Clone or copy this repository into your Sublime Text `Packages/User` directory
(**Preferences → Browse Packages…**).

## Activating

- **Color scheme:** **Preferences → Select Color Scheme…** → `Gold Rose`.
- **UI theme:** **Preferences → Select Theme…** → `Gold Rose`.

## Palette

| Role        | Hex       |
|-------------|-----------|
| Background  | `#1a1416` |
| Foreground  | `#e6bfa8` |
| Accent      | `#B76E79` |
| Rose        | `#c96b7a` |
| Sage        | `#a3b18a` |
| Gold        | `#d4a373` |
| Slate       | `#8896b0` |

## License

Released under the [MIT License](LICENSE).
