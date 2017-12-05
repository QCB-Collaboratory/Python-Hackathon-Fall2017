# Integrating camera and arduino

In many applications, organic compounds are used as fluorescence tracer. LEDs are often use to excite these compounds, which then emit radiation in a different wavelength. [Fluorescein](https://en.wikipedia.org/wiki/Fluorescein), for instance, is used in a broad range of applications, from cell miscroscopy to forensics. The idea of this project is to use Python to syncrhonize LEDs and camera.

<img src="https://raw.githubusercontent.com/thmosqueiro/UCLA-Collaboratory_Hackathon/master/Materials_Resources/Problem-5/resources/scheme_arduino_pc.png" with=70% />

### Primary goal

By the end of this project, we should have an acquisition system that synchronizes an array of LEDs with a camera. You should be able to control the sampling rate and the exposition of the LEDs (which controls for photobleach).


### Technical challenges

* Use Python to synchronize an LED array and a camera

* Writing very simple code for arduino

* Control a camera from Python


### Guideline

1. Write a Python script/module that communicates with a camera and an arduino

2. Make the camera take picture after the arduino has turned on LEDs.

3. Control the interval between each shots with a parameters ```delta```. How small can ```delta``` be?

4. What is the best way to keep track of time?

5. Modify your system to, instead of controlling the time interval between shots, take ```Nshots``` per second.


### Resources

* To send signals from the computer to the arduino board, you will use the serial port.
  * [Software Serial Example](https://www.arduino.cc/en/Tutorial/SoftwareSerialExample), from arduino's website.
  * [YouTube tutorial](https://www.youtube.com/watch?v=ts81ZTdY_DQ) with an example of an arduino using commands from a computer
  * [Example](https://github.com/thmosqueiro/PlaygroundINO/tree/master/Medium-Projects/LeakyIntegratino) in a simple project that simulates a leaky integrate-and-fire neuron with arduino

* [OpenCV tutorial](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html) on how to capture video/frames
