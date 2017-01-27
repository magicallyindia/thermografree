# open-flir

This repository contains code and hardware design files for an open source forward looking infrared (FLIR) thermal camera.

The thermal camera is based on a Heimann Sensor module, detailed in ```docs/HeimannArrays9-9-16.pdf``` and the sample datasheet (```docs/HTPA 32x32d L2.1_0.8 (Hi)S Rev2 Datasheet.pdf```.) Previous attempts at open source thermal cameras have been based on the Melexis MLX90621. The datasheet for this part is also available at ```docs/MLX90621-Datasheet-Melexis.pdf```.

Code is in ```source/GUI/```, and should work out of the box on a Raspberry Pi with I2C enabled. It is dependent on OpenCV, and a handful of other Python packages.

Models for 3D printing are in ```case/```.

Research on noise characteristics of the camera and possible uses/limitations for gas sensing are archived in ```noise/```.
