# ICNS-Toolkit
Convert image from/to Apple Icon Image format (.icns)

# Introduction
According to [Wikipedia](https://en.wikipedia.org/wiki/Apple_Developer_Tools#Icon_Composer): 
>As of Xcode 8.2, Icon Composer is no longer available in Additional Tools, as it cannot create high resolution icons. Apple recommends using the command-line utility `iconutil`, which ships with macOS.

So there you go: 
![]()

# User Manual
With `Convert to Apple Icon Image format` App, you can drag your transparent PNG file on to it. The workflow application will automatically convert the picture into `.icns` icon file, placing on Desktop.

The `Convert to Apple Icon Image format` was built with macOS built-in utility `Automator`, feel free to open the app with it, and help debugging.

# Known Issue
* When `.png` icon with file name including spaces were inputed, the app will crash and leave a `.iconset` folder on Desktop.