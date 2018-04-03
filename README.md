# GRUFBA 3D
Gesture Dataset

This dataset was created at the **Federal University of Bahia**, **Brazil**, as part of the project presented to obtain a Master's degree in Computer Science, at the **Institute of Mathematics** and **PGCOMP (Graduate Program in Computing)**.

### Information
This dataset contains **7** gesture classes, recorded from **7** subjects, performing between **15-30** times each ones, totalizing **1099** samples. The track was recorded using a Microsoft Kinect sensor with the OpenNI library tracker.

### Files
This repository contains two files. The **gesture_raw.txt** contains the raw data, while the **gesture_origin.txt** is normalized and centralized at the origin using the centroid.

The gestures were splitted using the following structure:

```
gesture [class name] [number of hands]

X Y Z X Y Z

X Y Z X Y Z

...

...

X Y Z X Y Z

end
```

Where the first vector is the left hand, and the second is the right hand.
