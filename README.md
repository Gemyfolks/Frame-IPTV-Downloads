# Veyrith IPTV

Desktop player and Samsung TV developer preview for your own playlist. No channels, subscriptions or provider credentials are included.

[Website and playlist setup](https://luma-development.up.railway.app/en) · [Downloads](https://github.com/Gemyfolks/Veyrith-IPTV-Downloads/releases)

The website is available in English, Arabic, French, German, Spanish and Portuguese. Connect an Xtream Codes account or upload an M3U playlist, then import the private connection code in the app. Favorites and watch history stay on your device.

## Windows

Download and run Veyrith-IPTV-Windows.exe. It is portable and does not include your content or a testing account. You can also connect your provider directly in app settings.

## Samsung TV preview

The WGT is unsigned and cannot be installed as-is. Native Samsung playback, remote navigation and native keyboard integration are implemented, but physical TV playback and SmartThings phone typing have not yet been verified.

For developer installation, use Tizen Studio with the Samsung TV and certificate extensions. Enable Developer Mode on the TV, add your computer address, and create a Samsung author/distributor certificate with the TV DUID. Extract the unsigned WGT ZIP into a folder, then sign it using `tizen package -t wgt -s YOUR_PROFILE -- YOUR_WIDGET_FOLDER`. Install the resulting signed WGT on the connected TV. This is a developer preview, not a Samsung Store release.

[Samsung certificate instructions](https://developer.samsung.com/smarttv/develop/tools/additional-tools/vscode/creating-certificates.html)
