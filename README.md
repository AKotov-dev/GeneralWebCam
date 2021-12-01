# GeneralWebCam
Configuring the `uvcvideo` kernel module for `Generalplus Technology Inc. GENERAL WEBCAM`.

![](https://github.com/AKotov-dev/GeneralWebCam/blob/main/ScreenShot.png)

Dependencies: v4l-utils ffmpeg

After installing the package, restart the computer or disconnect the webcam and do the following:
```
su/password
rmmod uvcvideo
```
...and connect the webcam again.

Tested in Mageia-8 and LUbuntu-21.10.
