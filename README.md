# Touch-Projectors
This is demo code written in Python that can make any surface into an interactive touch pad.

This software will allow you to select four points on any surface and those points can act as a touch surface for your laptop. Typ

Hardware dependencies :

- Webcam (internal laptop webcam or usb webcam)
- LED pen with a button switch.


Software Dependencies:
- Python
- pyautogui
- pynput
- OpenCV

#### How to run the code : ####

1. Install the dependencies (Ubuntu or MacOS is preffered)

```bash
  sudo apt-get instal python-dev python-pip python-wheel
  pip install numpy
  pip install pyautogui
  sudo -H python -m pip install --upgrade pip setuptools wheel 
  sudo -H pip install xlib
  sudo -H pip install xlib>=0.17
  sudo -H pip install pynput
  pip install opencv-contrib-python
```
2. System Arrangement

Keep the camera faced to the projector and keep it fixed. 

![alt text](https://github.com/huzz/Touch-Projectors/blob/master/system_arrangement.png)

3. Run the code :
 ```bash
 python source.py
 ```
 Then select four points in the following order for the region of interest : top-left, top-right, bottom-left, bottom-right
  
4. Result:


![alt text](https://github.com/huzz/Touch-Projectors/blob/master/result.png)

#### LED pen schematic: ####

![alt text](https://github.com/huzz/Touch-Projectors/blob/master/pen_schematic.png)

