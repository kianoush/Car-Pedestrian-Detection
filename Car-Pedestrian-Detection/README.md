# Car-Pedestrian-Detection
Car &amp; Pedestrian Detection

Car & Pedestrian Detection

If no video loads after running code, you may need to copy your opencv_ffmpeg.dll
From: C:\opencv2413\opencv\sources\3rdparty\ffmpeg
To: Where your python is installed e.g. C:\Anaconda2\ \
Once it's copied you'll need to rename the file according to the version of OpenCV you're using.
e.g. if you're using OpenCV 2.4.13 then rename the file as:
opencv_ffmpeg2413_64.dll or opencv_ffmpeg2413.dll (if you're using an X86 machine)
opencv_ffmpeg310_64.dll or opencv_ffmpeg310.dll (if you're using an X86 machine)


To find out where you python.exe is installed, just run these two lines of code:

import sys
print(sys.executable)
