# MRCVolume viewer
Preview mrc volume in a simple viewer!

![](https://github.com/dzyla/MRCVolume_viewer/blob/master/7OwD44WAc61.gif)

## Requirements
Python 3+ / numpy / vtkplotter / mrcfile / easygui (optional)

## How to
run the script via command line or double click the file (windows). Script should automatically guess the starting threshold value of the volume to create the isosurface. It can be changed with the slider at the botton and the color with one at the top. For more functionality coming from VTKplotter click h:

![](https://github.com/dzyla/MRCVolume_viewer/blob/master/Capture.JPG)

## Limitations
Depending on the system setup, huge maps (300px+) might open very slowly and threshold level update might be not as smooth. I would suggest to not use low threshold values in those cases!
