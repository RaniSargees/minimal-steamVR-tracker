# minimal-steamVR-tracker
a bare-minimum hand-solderable steamVR tracker, based on http://hivetracker.github.io/

The firmware for this does not yet exist.

Arduino is incompatible with the nrf52810, so this design does not work with the hivetracker firmware. This can be changed by replacing the [Laird bl651](https://www.lairdconnect.com/wireless-modules/bluetooth-modules/bluetooth-5-modules/bl651-series-bluetooth-module) module with the compatible nrf52832-based [Laird bl652](https://www.lairdconnect.com/wireless-modules/bluetooth-modules/bluetooth-5-modules/bl652-series-bluetooth-v5-nfc-module). The design does not need to be changed.
