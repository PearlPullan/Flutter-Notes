# Flutter-Notes

1. AppBar(
  centerTitle: true, // this is all you need
  ...
)
2. Create app icons-> appicon.co
3. Color to text in AppBar
default is white
appBar: AppBar(
  title: Text(
    'Flutter Tutorial - googleflutter.com',
    style: TextStyle(color: Color(0xffffffaa)),
  ),
),
4. The Dart's SDK is located at C:\src\flutter\bin\cache\dart-sdk
5. Wideget catalog https://flutter.dev/docs/development/ui/widgets
6. https://medium.com/flutter-community/flutter-layout-cheat-sheet-5363348d037e
7.For a row, the main axis runs horizontally and the cross axis runs vertically. 
For a column, the main axis runs vertically and the cross axis runs horizontally.
8.There are icons already present that we can use
Icon(Icons.____)
we can change its colour and use as we like
https://api.flutter.dev/flutter/material/Icons-class.html
https://material.io/resources/icons/?style=baseline
https://www.materialpalette.com/
10. card class
11. ListTile
12.divider class
13. why is my flutter outline empty
Move the mouse to any widget and Press Ctrl and click on that widget , after this step, your FLutter Outline will be enabled
14. [ADB: failed to install /Users/rahama/development/flutter_uber_clone/build/app/outputs/apk/app.apk: Failure [INSTALL_FAILED_INSUFFICIENT_STORAGE] Error launching the application on Android SDK built for x86.]
(A)
Your Emulator is Running out of Space
clear its cache
Click on AVD Manager
Wipe Data (Your Target Device )
(B)
 run flutter upgrade in the terminal
