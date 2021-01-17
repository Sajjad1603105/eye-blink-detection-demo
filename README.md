# eye-blink-detection-demo

 A very simple demo code for eye blink detection with dlib libray with python, Note this project is basically dependent on the library dlib.
## Environment
* win10
* python 3.5.4
* opencv 3.3.1
* imutils 0.4.6
* dlib 18.18
* Anaconda3

## install packages
```
conda intall dlib
conda install opencv3
pip install imutils
```

## sample 
open the terminal 
```
python detect_blinks.py
```
The default args open the camera and detect the eye blink in the video

You can see more information about the args, parse a larger **threshold** means an eye can be more easily considered as closed, vice versa.parse a larger **frames** means only if the closed eyes last for more frames, can it be considered as a closed eye.You can aslo parse a video file by parsing **video** args. the **shape-predictor** args indicate the trained model path which is provided in the demo


