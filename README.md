# Wingg plugin for Claude Code

This is the Claude Code plugin for [Wingg](https://github.com/augustohub/wingg-releases), a macOS app that puts two bars of widgets beside the Dock.

The plugin sends Claude Code's session events to Wingg. Its Agents tile then shows which sessions are running, which ones need you, and which ones are done.

## Install

Run these two commands inside Claude Code:

```
/plugin marketplace add augustohub/wingg-plugin
/plugin install wingg@wingg
```

Then start a new Claude Code session, so the hooks load.

## It needs the Wingg app

The plugin only passes events on. The Wingg app does the work. Without the app, the plugin does nothing.

Get Wingg here: https://github.com/augustohub/wingg-releases/releases/latest/download/Wingg.zip

Or with Homebrew:

```
brew tap augustohub/wingg
brew trust --cask augustohub/wingg/wingg
brew install --cask augustohub/wingg/wingg
```
