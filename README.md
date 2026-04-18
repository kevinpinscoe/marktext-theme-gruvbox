# marktext-theme-gruvbox

A Gruvbox Dark export theme for [Mark Text](https://github.com/marktext/marktext), based on the [Gruvbox](https://github.com/morhetz/gruvbox) palette by morhetz.

## Preview

Renders exported documents with the full Gruvbox dark palette:

| Element | Color |
|---------|-------|
| Background | `#282828` |
| Foreground | `#ebdbb2` |
| H1 | `#fabd2f` (bright yellow) |
| H2 | `#83a598` (bright blue) |
| H3 | `#b8bb26` (bright green) |
| H4 | `#fe8019` (bright orange) |
| Code | `#b8bb26` on `#3c3836` |
| Code blocks | `#ebdbb2` on `#1d2021` |
| Blockquote | `#d79921` border, `#32302f` background |
| Links | `#83a598` |
| Strong | `#fabd2f` |
| Em | `#b8bb26` |

## Installation

### Fedora (Flatpak)

```bash
cp gruvbox.theme.css ~/.var/app/com.github.marktext.marktext/config/marktext/themes/export/
```

### Fedora (native install)

```bash
cp gruvbox.theme.css ~/.config/marktext/themes/export/
```

### macOS

```bash
cp gruvbox.theme.css ~/Library/Application\ Support/marktext/themes/export/
```

Restart Mark Text after copying. The theme will appear as **Gruvbox Dark** in **Preferences → Export → Theme**.

## Customization

The palette variables are documented in comments at the top of `gruvbox.theme.css`. To switch to a lighter contrast variant, swap `#282828` (bg0) for `#1d2021` (bg0_h) throughout, or adjust accent colors using the bright variants (`bred`, `bgreen`, etc.).

## Credits

- Gruvbox palette: [morhetz/gruvbox](https://github.com/morhetz/gruvbox)
- Mark Text export theme docs: [EXPORT_THEMES.md](https://github.com/marktext/marktext/blob/master/docs/EXPORT_THEMES.md)
