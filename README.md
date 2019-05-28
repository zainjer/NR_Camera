# NR_Camera

App requirment Specifications 

Two modes:
1- Capture on pressing volume button (like in selfie stick)
2- Capture continuously after X delay seconds (volume button to start and stop capturing)

While saving, it should generate two files:
1- The actual image file (filename: date-time.jpg)
2- The data file (filename: date-time.txt)
(the date-time for both the files should be same)

In the data file, I need the following information:
- Date (Day/Month/Year)
- Time (24hrs hh:mm:ss)
- GPS Latitude
- GPS Longitude
- Compass direction (0-360 degrees, where 0 towards magnetic north, apply corrections for the tilted phone)
- Pitch angle
- Roll angle

Note that, I do not want any information overlayed on the image, not even when viewing it.

There should be a settings panel as well to configure:
- Folder to save files (default: "MyCamera")
- X delay (in seconds) for mode 2
- Resolution: high, medium or low
- Shutter sound: On/Off
Orientation: Portrait/Landscape

As the app will be used for long hours without being interacted with the phone, so the app should work in the background as well.
