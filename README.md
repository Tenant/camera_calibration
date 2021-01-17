## 1. Usage

Assume that the repository path on your machine is `$ROOTDIR`, then use the following command to compile and run the calibration program:

```bash
cd $ROOTDIR
mkdir -p release
cd release
cmake ..
make -j
```

```bash
./calibrate -w 1920 -h 1080 -s 20 -i $DATADIR -p "" -e ".png" --camera-model "pinhole"
```



## Reference

[HKUST-Aerial-Robotics/VINS-Mono: A Robust and Versatile Monocular Visual-Inertial State Estimator (github.com)](https://github.com/HKUST-Aerial-Robotics/VINS-Mono)

[hengli/camodocal: CamOdoCal: Automatic Intrinsic and Extrinsic Calibration of a Rig with Multiple Generic Cameras and Odometry (github.com)](https://github.com/hengli/camodocal)

