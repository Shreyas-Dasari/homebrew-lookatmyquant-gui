# homebrew-lookatmyquant-gui

Homebrew tap for [LookAtMyQuant-Gui](https://github.com/Shreyas-Dasari/LookAtMyQuant-Gui), a Mac desktop launcher for running LookAtMyQuant models locally. Homebrew requires trusting third-party taps before installing, and the cask strips Apple's quarantine flag automatically during install:

```bash
brew tap Shreyas-Dasari/lookatmyquant-gui
brew trust shreyas-dasari/lookatmyquant-gui
brew install --cask lookatmyquant-gui
```
