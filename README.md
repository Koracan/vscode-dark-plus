# VS Code Dark+ Complete

A faithful, complete port of [VS Code](https://github.com/microsoft/vscode)'s **Dark+** theme to
[Zed](https://zed.dev), with a focus on covering everything the Zed theme format supports.

Unlike a plain color dump, this extension also styles every syntax node Zed's built-in themes
use — so Rust `enum`/`variant`, Markdown headings and links, CSS selectors, inlay hints,
inline predictions and `diff` nodes look the way they do in VS Code.

## Installation

Search for **VS Code Dark+ Complete** in Zed's extension list (`zed: extensions`), install it,
then pick the theme via `zed: theme selector` (or with `theme = "VS Code Dark+ Complete"` in
`settings.json`).

To install it as a dev extension from a local checkout: run `zed: install dev extension` and
select this directory.

## What it covers

- **UI**: title/tab/status bars, panels, panes, elements, ghost elements, editors, gutter,
  scrollbars, minimap, terminal (ANSI normal/bright), search highlights, diagnostics
  (error/warning/info/hint), version control and conflict markers, players.
- **Syntax**: 50 syntax nodes, including the ones a plain VS Code port usually misses —
  `emphasis`, `enum`, `variant`, `namespace`, `label`, `title`, `link_text`, `link_uri`,
  `selector`, `selector.pseudo`, `punctuation.markup`, `variable.parameter`,
  `function.builtin`, `hint`, `predictive`, `diff.plus`, `diff.minus`.

## Credits

All colors are ported from Microsoft's VS Code theme defaults
([`dark_vs.json`](https://github.com/microsoft/vscode/blob/main/extensions/theme-defaults/themes/dark_vs.json)
and [`dark_plus.json`](https://github.com/microsoft/vscode/blob/main/extensions/theme-defaults/themes/dark_plus.json)),
which are licensed under the MIT License. This extension is not affiliated with or endorsed by
Microsoft or the VS Code team.

## License

MIT — see [LICENSE](./LICENSE).
