# yazi-plugins

A collection of small, focused plugins for the [Yazi](https://github.com/sxyazi/yazi) file manager.

## Plugins

| Plugin | Description |
| --- | --- |
| [`lint.yazi`](./lint.yazi) | Lint the hovered file and show the result via a notification. |

## Installation

Plugins in this repo are installed individually via Yazi's package manager, using `owner/repo:subdir` syntax:

```sh
ya pkg add barabasz/yazi-plugins:lint
```

Or manually:

```sh
git clone https://github.com/barabasz/yazi-plugins.git
cp -r yazi-plugins/lint.yazi ~/.config/yazi/plugins/
```

See each plugin's own README for keybinding and configuration details.

## License

MIT — see each plugin's own `LICENSE` file.
