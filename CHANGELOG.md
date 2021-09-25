## 0.3.1
- Add bulkTransferIn,bulkTransferOut timeout parameter.

## 0.3.0

- Add `getDevicesWithDescription`
- Add `getDeviceDescription`
- Add `detachKernelDriver`
- [Fix `dylib` @rpath on macOS](https://github.com/woodemi/quick_usb/issues/23)
- Refactor linux so loading

## 0.2.0

- Migrate to null safety

## 0.1.0+2

- Fix bulkTransferOut length limit on Android
- Return negative length when bulkTransferOut error on desktop

## 0.1.0+1

- Fix README

## 0.1.0

Add several APIs

* `hasPermission`/`requestPermission`
* `openDevice`/`closeDevice`
* `getConfiguration`/`setConfiguration`
* `claimInterface`/`releaseInterface`
* `bulkTransferIn`/`bulkTransferOut`

## 0.0.1

* Add `init`, `exit` and `getDeviceList`
