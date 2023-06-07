# SwitchCon
ESP32 compatible Nintendo Switch controller.

![](https://i.imgur.com/HjPuPFi.png)

This is an amalgamation of the amazing works of [Nathan Reeves](https://github.com/NathanReeves/BlueCubeMod) and [wchill](https://github.com/wchill/SwitchInputEmulator).

Huge thanks to [mizuyoukan-ao](https://github.com/mizuyoukanao) for figuring out v12 Switch Firmware support!

This gives users an easy to control their Nintendo Switch with a custom controller.

The ESP32 can act as a Left or Right Joy-Con, or a Pro Controller. (Wireless only)

- Left Joy-Con is the recommended usage, as it has the least amount of fiddlyness.

The protocol is described in Protocol.md. It is a carbon copy of SwitchInputEmulator's protocol, with the addition of SL and SR. 

This was forked from [UARTSwitchCon](https://github.com/nullstalgia/UARTSwitchCon) and converted to be used as a standalone controller
