# High-quality Ellipse Detection（Ubuntu20.04 version & OpenCV4）

> Migrate [High-quality Ellipse Detection](https://github.com/AlanLuSun/High-quality-ellipse-detection)to Ubuntu20.04(x86) with OpenCV 4.5.5
>
> * Modified `generateEllipseCandidates.cpp` to adapt OpenCV4
> * Compiling under Ubuntu 20.04

## Compile commands
The following command is executed at the matlab command line
```
mex -I/usr/include/opencv4/ generateEllipseCandidates.cpp
```
which would generate `generateEllipseCandidates.mexa64`

I have put my compiled files into this repo.



