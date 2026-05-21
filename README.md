# Air Theme für Zed

<p align="center">
  <img src="air-theme.png" width="128" alt="Air Theme Logo" />
</p>

Zed-Port von [JetBrains Air](https://github.com/franzgollhammer/air-theme-vscode) — ruhige Theme-Familie mit lavendelfarbenen Keywords, pinken Strings, bernsteinfarbenen Zahlen und grünen Typen.

## Varianten

Vier Varianten enthalten:

- **Air Dark** — Dunkles Theme
- **Air Dark Italic** — Dunkel mit kursiven Parametern/Strings und fetten Funktionen
- **Air Light** — Helles Theme
- **Air Light Italic** — Hell mit kursiven Parametern/Strings und fetten Funktionen

### Air Dark

![Air Dark](preview-dark.png)

### Air Dark Italic

![Air Dark Italic](preview-air-theme-dark-italic.png)

### Air Light

![Air Light](preview-light.png)

### Air Light Italic

![Air Light Italic](preview-air-theme-light-italic.png)

### Italic-Stile

| Token | Stil |
|-------|------|
| `function`, `function.method`, `function.builtin` | **fett** |
| `variable.parameter` | *kursiv* |
| `string`, `string.escape`, `string.regex` | *kursiv* |
| `comment` | *kursiv* (alle Varianten) |

## Installation

### Aus dem Extensions-Tab

1. `cmd+shift+x` → Extensions öffnen
2. Nach "Air Theme" suchen
3. Install klicken
4. `cmd+k cmd+t` → Variante wählen

### Manuell (Dev Extension)

```bash
git clone https://github.com/franzgollhammer/air-theme-zed
```

1. Zed öffnen
2. `cmd+shift+p` → `zed: install dev extension`
3. Geklonten Ordner wählen
4. `cmd+k cmd+t` → Variante wählen

## Terminal Themes

Passende Terminal-Themes im Ordner `terminal-themes/`:

- **Ghostty** — `terminal-themes/ghostty/air-dark`, `air-light`
- **iTerm2** — `terminal-themes/iterm2/air-dark.itermcolors`, `air-light.itermcolors`
- **Warp** — `terminal-themes/warp/air-dark.yaml`, `air-light.yaml`

## Farbpalette

### Dark

| Rolle | Hex |
|-------|-----|
| Background | `#18191B` |
| Foreground | `#dddddd` |
| Comment | `#909192` |
| String | `#E394DC` |
| Keyword | `#82D2CE` |
| Function | `#F8C762` |
| Type | `#EFB080` |
| Variable | `#AAA0FA` |
| Parameter | `#A8CC7C` |
| Number | `#EBC88D` |
| Tag | `#87C3FF` |

### Light

| Rolle | Hex |
|-------|-----|
| Background | `#FBFBFC` |
| Foreground | `#1F2024` |
| Comment | `#8C8C8C` |
| String | `#B03A88` |
| Keyword | `#1F7F78` |
| Function | `#8D6B1F` |
| Type | `#A85A29` |
| Variable | `#5A4ECF` |
| Parameter | `#4E7A2A` |
| Number | `#8F6614` |
| Tag | `#1C5DB5` |

## Verwandte Projekte

- [Air Theme für VSCode](https://github.com/franzgollhammer/air-theme-vscode)
- [JetBrains Air (Original)](https://www.jetbrains.com/help/idea/working-with-themes.html)

## Publishing

Siehe [Zed Extensions Docs](https://zed.dev/docs/extensions/themes).

PR gegen [zed-industries/extensions](https://github.com/zed-industries/extensions):

```bash
git submodule add https://github.com/franzgollhammer/air-theme-zed extensions/air-theme
```

`extensions.toml` erweitern:

```toml
[air-theme]
submodule = "extensions/air-theme"
version = "0.1.0"
```

## Lizenz

MIT
