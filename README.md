# UsbDk

UsbDk (USB Development Kit) is a open-source library for Windows meant
to provide user mode applications with direct and exclusive access to
USB devices by detaching those from Windows PNP manager and device drivers
and providing user mode with API for USB-specific operations on the device.

The library is intended to be as generic as possible, support  all types of
USB devices, bulk and isochronous transfers, composite devices etc.

Library supports all Windows OS versions starting from Windows XP/2003.

## Documentation

* See ARCHITECTURE document in the source tree root.
* See Documentation folder in the source tree root.
* See UsbDkHelper\UsbDkHelper.h UsbDkHelper\UsbDkHelperHider.h for API documentation

## Building

**Tools required:**

* Visual Studio 2013/Visual Studio 2013 Express update 4 or newer
* WDK 8.1
* WDK 7.1 (for Windows XP/2003/Vista/2008 builds)

***Compilation***

Just open UsbDk.sln from the source tree root in Visual Studio 2013 and compile
desired configuration.

## Installing and running

Use UsbDkController.exe to install/uninstall and verify basic operation.
Run UsbDkController.exe without parameters for command line options.
