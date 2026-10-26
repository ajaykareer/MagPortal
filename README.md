# MagPortal

A free personal live TV and VOD player for Windows and the browser.

**[Download MagPortal for Windows](https://github.com/ajaykareer/MagPortal/releases/latest)** · **[Open the browser player](https://magportal-player.goli15.chatgpt.site)**

## Windows installation

1. Download `MagPortal-Setup-0.2.2.exe` from the release assets.
2. Run the installer for your Windows account.
3. Open **MagPortal** from the desktop or Start menu.
4. Enter your own provider details or import an authorized M3U playlist.

Windows 10/11, 64-bit. The runtime and private local server are included. No separate Node installation, batch file, hosting subscription, or paid signing service is required. The installer is unsigned; Windows may display an unknown-publisher warning.

## Features

- Provider M3U playlists, Xtream live TV, and authenticated MAG/Stalker portal browsing.
- Live TV, movies, series, favorites, and saved viewing progress where supplied by your provider.
- Local subtitle files and optional subtitle API configuration.
- Encrypted Windows app data, a private loopback server, and a sandboxed app window.
- Fresh sign-in on Connect, automatic renewal of an expired provider session, and an Open Windows app button on the website.
- MAC address validation before contacting a MAG provider.

MagPortal is free to download and use as a personal player. It includes no channels, subscriptions, shared accounts, or provider credentials. You must supply details legitimately assigned to you and have permission to use the content. Provider subscription fees, if any, are separate.

## Browser version

Open [MagPortal Web](https://magportal-player.goli15.chatgpt.site). No ChatGPT account is needed. Enter your own provider URL and assigned MAC address, then choose **Connect**. Guest access starts automatically; allow this site's cookies. ChatGPT sign-in is optional. The browser version loads channel groups in batches and uses a bounded media relay for protected playback, including supported HTTP sources. Playback links are encrypted, expire, and require the matching guest browser or signed-in account. Saved details remain in the current browser tab; changing the browser identity clears them.

The hosted player runs independently of your PC. Compatible video formats and provider session rules still apply; some sources require the Windows app. Generic playlists can play directly when their HTTPS and cross-origin settings permit it. Free hosting has usage limits; availability is not guaranteed. No paid app account or paid service was added.

See [privacy and compatibility details](https://magportal-player.goli15.chatgpt.site/privacy).

## Existing profiles and subtitles

Use **Export Data** in an existing MagPortal browser session, then **Import Data** in the Windows app. Exported JSON includes saved credentials; keep backups private.

To configure subtitle API credentials, choose **File > Import subtitle settings** in the Windows app and select your own `local.settings.json`. Personal settings are never included in the download.

## Releases

This repository hosts public installers, checksums, and release notes. The Windows app uses the Chromium media player and does not transcode unsupported formats. Verify the installer against the published `SHA256SUMS.txt` if needed.
