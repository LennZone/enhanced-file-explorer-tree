# Contributing

Thanks for your interest in improving Enhanced file explorer tree. Bug reports, ideas and pull requests are all welcome.

## Reporting a bug

Please [open an issue](https://github.com/LennZone/enhanced-file-explorer-tree/issues/new/choose) and include:

- your Obsidian version and platform (Windows, macOS, Linux, Android, iOS)
- light or dark mode
- a screenshot of the file explorer showing the problem
- CSS snippets or plugins that change the file explorer, if any

## Suggesting a change

For larger changes, please open an issue first so I can give feedback on the idea before you spend time on it.

## Design rules

- **Minimal**: the theme only changes the file explorer. Everything else stays Obsidian's default look.
- **Follow Obsidian's layout**: positions and sizes come from Obsidian's own variables, not from fixed pixel values, so the lines stay aligned with other font sizes, zoom levels and on mobile.
- **Customizable through variables**: new options are `--eft-*` variables that can be overridden in a CSS snippet. Please document them in the README.

## Working on the theme

The whole theme lives in `theme.css`. The comment at the top explains how the lines are drawn.

1. Fork the repository and clone it.
2. Link or copy the folder into a test vault at `.obsidian/themes/Enhanced file explorer tree`.
3. Select the theme under Settings, Appearance, Themes.
4. After saving `theme.css`, reload the theme (switch to another theme and back, or run "Reload app without saving").

Before opening a pull request, please check:

- light and dark mode
- deeply nested folders, collapsed and expanded
- a larger and a smaller font size or zoom level
- if you can, mobile and the right sidebar

## Pull requests

- Keep a pull request focused on one change.
- Add before and after screenshots for visual changes.
- Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, for example `fix(theme): align corner on last item`.

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
