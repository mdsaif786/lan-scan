# lan-scan

Finding devices on a local network can be useful when checking Wi-Fi connectivity or identifying hosts on the same LAN. **lan-scan provides an iOS app for scanning the local Wi-Fi network.**

## Features

- Scan the local Wi-Fi or LAN network from an iOS device.
- Discover devices connected to the same local network.
- Display scan results inside the app.

## Installation

Clone the repository and open the Xcode project:

```sh
git clone https://github.com/your-org/lan-scan.git
cd lan-scan
open lan-scan.xcodeproj
```

Select an iOS Simulator or a connected iOS device in Xcode, then build and run the app. Use a device connected to the network you want to scan.

## Usage

Build the app for an iOS Simulator with `xcodebuild`:

```sh
xcodebuild -project lan-scan.xcodeproj \
  -scheme lan-scan \
  -destination 'platform=iOS Simulator,name=iPhone 15' \
  build
```

Launch the app from Xcode or the simulator, then start a scan from the app interface. The scan covers the local network used by the iOS device or simulator.

## License

lan-scan is released under the MIT License.

This project is based on [mongizaidi/LAN-Scan](https://github.com/mongizaidi/LAN-Scan), an iOS Local Area Network scanner. See the `LICENSE` file for the full license text and attribution details.
