# Haptic Pen Motion Tracking and Plotting

This program is used to track the motion of a haptic pen on a whiteboard and plot the pen's relative X and Y coordinates over time.
The project will be constantly updated.

## Getting Started

### Prerequisites

What things you need to run the program

* This installation tutorial is for Windows. For Mac OS X please refer to [this website](http://frankfineis.github.io/blog/2016/03/13/install_opencv.html)
* Install Anaconda from https://www.anaconda.com/
* Install OpenCV from https://opencv.org/releases.html, choose either 2.X.X.X or 3.X.X version

### Installing Libraries

After both installations are done, copy the cv2.pyd file in the OpenCV installation folder to Anaconda side-package folder.
Example: I am using Python 2.7 and OpenCV 3.2. so I copy cv2.pyd under the directory
```
OpenCV3.2\opencv\build\python\2.7\x64
```
to directory 
```
Anaconda3\Lib\site-packages
``` 
You can also put multiple versions of OpenCV under site-package folder and switch among them simply by changing the desired .pyd file's name to "cv2.pyd". 

If you want to run this program under different environments, simply create virtual environement using conda. Please follow [this website](https://conda.io/docs/user-guide/tasks/manage-python.html) for details.

Install Matplotlib using command
```
conda install -c conda-forge matplotlib
```

After all installations are done, try to run the program using command
```
python track_plot.py
```
### Possible Trouble Shooting

Will add more information later.

## Authors

* **Yuxiang Huang** 

## Acknowledgments

* Udemy Computer Vision course taught by Rajeev Ratan
* Adrian Rosebrock from PyImageSearch