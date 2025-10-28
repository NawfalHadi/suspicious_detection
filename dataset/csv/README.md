# Dataset Version
give an explantion for every version of dataset

### Versi 0
it use for check how good are the detection of mediapipe after the frame cropped with human detection YOLOv12, the dataset is only containt landmark x,y,z,visibility from mediapipe model after detecting nose, ear left, ear right, wrist left, and wrist right. as much as frame which is 15 frames. then the features of the dataset is (15frames x (4landmarks x 5part)). with class.

<!-- insert table to explain feature -->

### Versi 1

additional of 3 features for each frames. which is as extended feature contains: <br>
- *Face Direction* : looking at left, center, or right, as helper to check celingak celinguk 
- *Body Direction* : check the body state facing front or back.
- *Hands Shown* : helping class to decide if the hands are shown to the camera. which is for showing what someone hold.

