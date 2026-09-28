<div align="center">
    <img src="images/AppIcon-512.png" width=200 height=200>
    <h1>ReMate</h1>
</div>

ReMate is a Spotify Remote control for Spotify Connect using Spotify API.

NB. This app requires premium Spotify account as needs developer account setup required for Web API.

The app does not have access to you playlists/songs/etc. It can only control what's being played and alllows you to control the player. It can't switch to non-active Spotify Connect devices such as phones and laptop if Spotify is not running on them. It switch to Echo speakers though.

[![Download](https://img.shields.io/badge/download-latest-brightgreen?style=flat-square)](https://github.com/tbrek/ReMate-Releases/releases/)
![Platform](https://img.shields.io/badge/platform-macOS-blue?style=flat-square)
![Requirements](https://img.shields.io/badge/requirements-macOS%2014%2B-fa4e49?style=flat-square)
[![Sponsor](https://img.shields.io/badge/Sponsor%20%E2%9D%A4%EF%B8%8F-8A2BE2?style=flat-square)](https://buymeacoffee.com/panukracy)
[![License](https://img.shields.io/github/license/jordanbaird/Ice?style=flat-square)](LICENSE)
<!-- [![Website](https://img.shields.io/badge/Website-015FBA?style=flat-square)]() -->


<div align="center">
<a href="https://buymeacoffee.com/panukracy" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;">
</a>
</div>

## Install

### Manual Installation

Download the "ReMate 1.01.dmg" file from the [latest release](https://github.com/tbrek/ReMate-Releases/releases/) double click dmg files the app into your `Applications` folder.

### ReMate features:

- Controls Spotify Connect devices via web API
- Can be docked in Menu Bar or float on the screen
- Can be set as Always on Top for "Always-on" control
- It has two screen modes - mini and large (normal)
- It can be set to Dark/Light or Auto modes

### Setup

- Visit [Spotify for Developers](https://developer.spotify.com)
- Login and go to your [Dashboard](https://developer.spotify.com/dashboard)
- Click Create app and fill the following details as per screenshot:
![Spotify Dev Setup](/images/Dashboard-Setup.png)
- When you click save you'll see confirmation screen with you Client ID
![Spotify Dev Client ID](/images/Client-Id-Setup.png)
- Copy client ID and close then browser window
- Open ReMate and you'll be asked to enter Client ID and login to Spotify
- You'll be asked to Authorize ReMate with Spotify
![Authorize-Spotify](/images/Authorize-Spotify.png)


## Gallery

#### Mini Remote

![Mini Remote](/images/Floating-Mini.png)

#### Large Remote

![Large Remote](/images/Floating-Large.png)

#### Mini Docked Remote

![MMini Docked Remote](/images/Docked-Mini.png)

#### Large Docked Remote

![Large Docked Remote](/images/Docked-Large.png)

#### Client ID setup window

![Client ID setup window](/images/Setup.png)

## License

Ice is available under the [GPL-3.0 license](LICENSE).