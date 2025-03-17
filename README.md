# Camera Calibration

We explore different methods of calibration for different goals. Camera
calibration usually refers to the acquisition of intrinsic matrix specific to
that camera, however, though uncommon, it might also means to get the extrinsic
matrix. Intrinsic matrix describes the camera's virtual geometry, or the
scene's transformation from 3D to 2D. Extrinsic matrix describes the
information of the camera in real world, such as its relative position, or its
tilting angles.

Currently, we want to try:

- Intrinsic camera calibration with a chess board
- Intrinsic and extrinsic camera calibration for a systems of multiple cameras
with a chess board
- Intrinsic and extrinsic camera calibration for single camera with
ArUco/ChArUco

> [!NOTE]
> This is an education project, so I bear no responsibilities for end-users.

# Reference/Resource

- <https://youtu.be/_-BTKiamRTg?si=6sR3nzWhaVHolsEe>
- <https://youtu.be/yKypaVl6qQo?si=UosjFBEIxVf3QtRm>
- <https://rtc-fukushima.jp/technical/5892/>

## Camera Calibration

- [Gentle Introduction using OpenCV](https://docs.opencv.org/4.x/dc/dbb/tutorial_py_calibration.html)
- [Implementation](https://github.com/luckykk273/Camera-Calibration/tree/main)
- [Video: Theory: Camera Calibration using Zhang's Method](https://www.youtube.com/watch?v=-9He7Nu3u8s)
