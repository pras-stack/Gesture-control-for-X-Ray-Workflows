# How to run these models
1. If you are using PyCharm IDE then you can simply create a new project and add these files to your project. 
Install opencv-python, mediapipe, cvzone and numpy

(You can install them by following the given path in PyCharm IDE 
File-> Setting-> Project: name_of_your_project -> Pyton interpreter ->
Here by clicking the + button you can install all required packages.)
And that's it! You are good to go. You can run the three models individually and see their features.

2. If you are using any other IDE, make sure you install virtualenv by running
  py -m pip install --user virtualenv
Install opencv-python, mediapipe, cvzone and numpy
And that's it! You are good to go. You can run the three models individually and see their features.

# How to operate these models
1. Gesture Voltage controller:
  Stretch one of your hand in front of the camera. You can control the voltage by changing distance between thumb and index finger. Lower your pinky finger to set the voltage.
  The obtained voltage can be fed to the machine for further process.
  
2. Virtual Control Panel:
  When you run this, a virtual control panel will pop up in front of you. Stretch one of your hands and move it. Join your index and middle finger tips on the button you want to click. First you set age, then type of x ray you want to perform. After that click enter. This can be used to feed these details to the x ray machine.
  
3. Virtual zoom gesture:
  Stretch both of your hands in front of the camera. Then lower all fingers except the thumb and the index finger of both the hands. The already uploaded image will appear and you can change the size of it by changing the distance between both of your index fingers. This can be used by surgeons to analyze x ray images standing away from the display monitors and hence simplify the whole process.

