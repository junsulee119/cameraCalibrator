# Camera Calibration Report

## Overview

Performed both camera calibration and distortion correction on iPhone 12 pro 1.0x camera, 0.5x camera, and Galaxy S9 1.0x camera.

| Camera              | Spec                    |
|---------------------|-------------------------|
| iPhone 12 pro 1.0x  |  ƒ/1.6 & 26 mm ~ 35 mm  |
| iPhone 12 pro 0.5x  |  ƒ/2.4 & 120°, 13 mm    |
| Galaxy S9 1.0x      |  ƒ/1.5·2.4 & 77°        |

## Camera Calibration Results

### iPhone 12 Pro - 1x Zoom Camera

| Parameter | Value |
|-----------|-------|
| Number of selected images | 52 |
| RMS error | 0.3133615998688047 |
| Camera matrix (K) | [[1.11627287e+03 0.00000000e+00 6.41543816e+02]<br>[0.00000000e+00 1.11660375e+03 3.45253748e+02]<br>[0.00000000e+00 0.00000000e+00 1.00000000e+00]] |
| Distortion coefficient<br>(k1, k2, p1, p2, k3, ...) | [1.91785858e-01 -8.45329913e-01 -3.28389992e-03 1.33403506e-03 1.40372357e+00] |

### iPhone 12 Pro - 0.5x Zoom Camera

| Parameter | Value |
|-----------|-------|
| Number of selected images | 38 |
| RMS error | 0.21947411391955451 |
| Camera matrix (K) | [[593.75950041 0. 640.39940448]<br>[0. 593.83101072 353.20336736]<br>[0. 0. 1.]] |
| Distortion coefficient<br>(k1, k2, p1, p2, k3, ...) | [0.03705602 -0.10018448 -0.00198709 0.00126405 0.06901485] |

### Galaxy S9 1x Zoom Camera

| Parameter | Value |
|-----------|-------|
| Number of selected images | 39 |
| RMS error | 1.4201245356498229 |
| Camera matrix (K) | [[1.87571382e+03 0.00000000e+00 9.69343465e+02]<br>[0.00000000e+00 1.88038644e+03 5.23192095e+02]<br>[0.00000000e+00 0.00000000e+00 1.00000000e+00]] |
| Distortion coefficient<br>(k1, k2, p1, p2, k3, ...) | [3.76201845e-01 -2.44934467e+00 -2.56570063e-04 8.98629132e-04 4.94922146e+00] |

## Lens Distortion Correction Demo Video
- **iPhone 12 Pro - 1x Zoom Camera**:

  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PsvkZ4L9ow0/0.jpg)](https://www.youtube.com/watch?v=PsvkZ4L9ow0)
  
  ![Demo video](media/checkerboard_1x.mp4)
- **iPhone 12 Pro - 0.5x Zoom Camera**:  

  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/kkl4_dGyg-U/0.jpg)](https://www.youtube.com/watch?v=kkl4_dGyg-U)

  ![Demo video](media/checkerboard_05x.mp4)
- **Galaxy S9 1x Zoom Camera**:  

  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ZN4hkl2IXow/0.jpg)](https://www.youtube.com/watch?v=ZN4hkl2IXow)

  ![Demo video](media/checkerboard_android.mp4)  
