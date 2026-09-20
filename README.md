# 🔵 rofi-bt-manager
A Rofi-based Bluetooth manager for Linux
Manage Bluetooth devices and controller settings directly from a Rofi menu.
> A modern alternative to [rofi-bluetooth](https://github.com/nickclyde/rofi-bluetooth).
## ✨ Features
### Bluetooth controller
- Turn Bluetooth on/off
- Scan for nearby Bluetooth devices
- Toggle pairable mode
- Toggle discoverable mode
- Restart the Bluetooth pairing agent

### Bluetooth devices
- Connect / disconnect devices
- Pair / unpair devices
- Trust / untrust devices
- Remove devices
- Display device MAC addresses

## ⚙️ Requirements
- [BlueZ](https://github.com/bluez/bluez) (`bluetoothctl`)
- [Rofi](https://github.com/davatorium/rofi)

## 📦 Installation
```bash
git clone https://github.com/z4pdy/rofi-bt-manager
cd rofi-bt-manager
chmod +x rofi-bt-manager
```
## 🚀 Usage
Run the script to open the Bluetooth manager:

```bash
./rofi-bt-manager
```
Additional arguments passed to the script are forwarded to Rofi.

