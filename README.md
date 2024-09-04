# Windows 10 Mobile build 15400 for all supported devices!
This build is the *last ever* build that left Windows Phone build lab on Microsoft, which never got released due to discontinuation of WP. The build is extracted to cabs from the 15400 leak from a Lumia 830 device.

With these cabs, you can install 15400 on *any* device that can run 15254! Note the cabs are Test signed as they are unofficial.

## Installition Guide
- Ensure the device runs 15254 build
- Unlock the bootloader
- Install [Flight signing files](https://github.com/Empyreal96/W10M-16212-Guides/raw/main/SimpleFlightEnabler.zip) with this script.
- Reboot and set the Date to anything before September 5 2017
- Download the cabs from releases and extract them to a folder.
- Push provided cabs with iutool. (`iutool -V -p [path to folder of cabs you extracted]`).
  - Get iutool from [here](https://github.com/Empyreal96/Updating-WP-FFUs-Guide/raw/main/W10M_Tools.7z) if you don't have it.
- Wait for it to install
- Enjoy.

## Differences From 15254
- This build has a slightly improved Edge browser with much more settings on `about:flags`
- There is a smoother fade-in animation on apps on app switching screen (?)

## Known Issues
- Timezones are not available (list is empty on settings)

## Screenshots
Soon™

## Changelog
- Removed a Resolution package that was included by accident, preventing install

