# DevDocs Desktop

日本語説明ページは[こちら](https://github.com/egoist/devdocs-desktop/blob/master/README-ja.md)

[![version](https://img.shields.io/github/release/egoist/devdocs-desktop.svg?style=flat-square)](https://github.com/egoist/devdocs-desktop/releases)
[![downloads](https://img.shields.io/github/downloads/egoist/devdocs-desktop/total.svg?style=flat-square)](https://github.com/egoist/devdocs-desktop/releases)
[![downloads latest](https://img.shields.io/github/downloads/egoist/devdocs-desktop/latest/total.svg?style=flat-square)](https://github.com/egoist/devdocs-desktop/releases/latest)

[DevDocs.io](https://devdocs.io/) combines multiple API documentations in a fast, organized, and searchable interface. This is an unofficial desktop app for it.

![devdocs-preview](https://user-images.githubusercontent.com/8784712/27121730-11676ba8-511b-11e7-8c01-00444ee8501a.png)



## Features

### Background behavior

When closing the window, the app will continue running in the background, in the dock on macOS and the tray on Linux/Windows. Right-click the dock/tray icon and choose Quit to completely quit the app. On macOS, click the dock icon to show the window. On Linux, right-click the tray icon and choose Toggle to toggle the window. On Windows, click the tray icon to toggle the window.

### Built-in shortcuts

`devdocs` the website itself has great built-in shortcuts support, just check the `help` page in the app.

<img src="https://ooo.0o0.ooo/2017/06/14/59402442301b8.png" alt="help" width="300" />

## Planned features

Please consider [sponsoring me](http://github.com/sponsors/egoist) to accelerate development.

- Menubar mode: switch beween desktop mode and menubar mode
- Tabs support: allow to open documentation in a new tab

### Global shortcut

Use <kbd>Ctrl+Shift+D</kbd> (or <kbd>Command+Shift+D</kbd> on macOS) to toggle the app.

## Install

### Using Homebrew

```
brew cask install devdocs
```

### Manual download

You can manually download the latest release [here](https://github.com/egoist/devdocs-desktop/releases).

## Development

It's really easy to develop this app, no build tools like Webpack needed here, checkout [./app](/app) to get more:

```bash
npm install

npm run app
# edit files, save, refresh and it's done.
```

## Distribute

```bash
npm run dist
```

## License

MIT &copy; [EGOIST](https://github.com/egoist)
