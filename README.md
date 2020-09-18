# Device

[![Language][lang-image]][lang-url]
[![License][license-image]][license-url]
[![Platform][platform-image]][cocoapod-url]

Super-lightweight library to detect used device

`Device.swift` extends the `UIDevice` class by adding a property:

```swift
var deviceType: DeviceType
```

## Install

### Swift packages

```swift
dependencies: [
    .package(url:"https://github.com/joaoduartemariucio/Device.swift", from: "1.3.0")
]
```

## Usage

```swift
import Device

// Use import Device_swift if you're using Cocoapods

let deviceType = UIDevice.current.deviceType

switch deviceType {
  case .iPhone6SPlus: print("Do stuff for iPhone6S Plus")
  case .iPadMini: print("Do stuff for iPad mini")
  default: print("Check other available cases of DeviceType")
}
```

## Credits

Johannes Schickling
https://github.com/schickling