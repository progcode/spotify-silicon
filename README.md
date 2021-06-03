### SpotifySilicon
For MacOS Big Sur (Apple M1)

Since the original spotify app keeps crashing on mac, I  wrapped up the web player with an electron and turned it into M1 architecture.
The build also includes [widevine support](https://support.spotify.com/article/enable-the-spotify-web-player/) and is signed with [Castlab](https://github.com/castlabs/electron-releases) so you can play DRM-protected content without error.

## Download

The latest version of SpotifySilicon for macOS is available [here](https://github.com/progcode/spotify-silicon/releases).

**Currently only Macos 11.3+ supported**

## Features

- Fully supported online player
- Widevine

## Screenshots

<p align="center">
  <img src="https://assets-github.s3.amazonaws.com/repo/progcode/img/Screenshot+2021-06-03+at+20.56.15.png" />
</p>

----------
> **v1.0.0 (build 100):**
> - First version

## Development
Build your own version with this command. You must sign your app: https://github.com/nativefier/nativefier/blob/master/CATALOG.md#spotify

```nativefier "nativefier "https://play.spotify.com" --inject ./build/assets/js/service-worker-fix.js --icon ./build/assets/icons/spotify-multi-size.icns -a arm64 --widevine --internal-urls ".*" --name="SpotifySilicon" --app-version 1.0.0 --build-version 100 --width 1440 --height 900 --min-width 1440 --min-height 900 --fast-quit --user-agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.212 Safari/537.36" --disable-dev-tools"```
You can see available options [here](https://github.com/jiahaog/nativefier/blob/master/docs/api.md)

## License

MIT © [Iconocoders](https://iconocoders.com/license)

## Legal

This code is in no way affiliated with, authorised, maintained, sponsored or endorsed by Instagram or any of its affiliates or subsidiaries. This is an independent and unofficial Spotify app. Use it at your own risk.

