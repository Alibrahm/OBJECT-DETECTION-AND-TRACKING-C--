# OBJECT DETECTION AND TRACKING C++
Author: ALI IBRAHIM
softwares used: opencv-3.2.0 -vc14 and Arduino-1.8.5 windows
Make sure you import opencv to visual studio you can use this link (http://www.youtube.com/watch?v=cgo0UitHfp8) to guide you how to install opencv in visual studio
HARDWARE:

1. Servo Motors x 2
2. Webcam ( any webcam) x 1
3. Arduino Mega/Uno x 1
4. External Power Supply 5V x 1
5. BreadBoard x 1
6. Single Core connecting wires

!For the Exception errors thrown that you may face using Microsoft Visual Studio make sure you install Windows Universal CRT SDK component,which adds support for legacy Windows SDKs.
If the problem still persists, you should change the Target SDK in the Visual Studio Project : check whether the Windows SDK version is 10.0.15063.0.

In : Project -> Properties -> General -> Windows SDK Version -> select 10.0.15063.0.

Then errno.h and other standard files will be found and it will compile.