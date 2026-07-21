# LunarisDolby

App-only mirror of `LunarisDolby` from the `16` branch of
[`Pong-Development/hardware_dolby`](https://github.com/Pong-Development/hardware_dolby).

The leading `soong_namespace {}` in `Android.bp` makes this app independently
visible to Android Make/Soong without importing any Dolby HAL modules.

The scheduled GitHub Action synchronizes the app weekly and can also be run
manually from the Actions tab.
