User Interface
++++++++++++++++
Information Bar
==================================
.. image:: /images/informationbar.png
   :align: center
   

Information bar is displayed at the top right corner of the screen. This is where you can find metadata about each dataset.
There are two types of name labels, the label with larger text is county name followed by the municipality name.The number 
in white denotes the dataset id referring to datasets annotation. The other details availbale are the dataset name, 
time stamps,Number of points and the length of the dataset.


Measurements
==================================
.. |pictool| image:: /images/toolicon.png
   :width: 50

|pictool| **Measurement Tools**

Measurements are performed by use of left click on the mouse on the desired position and right click is needed to terminate
the process. Measurement can also be found under the tools section in the sidebar.
 
Angle
------------------------       
.. |picangle| image:: /images/angle.png
   :width: 50

|picangle| **Angle Measurement Tool**

This tool measures the tridimensional angle formed by the lines connecting three points.To start a measurement, click on the 
angle measurement icon, then left click on three desired position and the process will be automatically completed.The unit of
angle measurement is degree.

All red points are draggable to adjust their positions.


.. raw:: html

  <center>
    <video controls src="../_static/Angle.mp4" width ="500" height="300"></video>
  </center>



Point
------------------------
.. |picpoint| image:: /images/point.png
   :width: 50

|picpoint| **Point Measurement Tool**

This tool set a point at desired position and display its XYZ coordinate. To start a measurement, click on the point measurement
icon, then click on the desired position and the process will be completed. All red points are draggable to adjust their 
positions.


.. raw:: html

  <center>
    <video controls src="../_static/Point.mp4" width ="500" height="300"></video>
  </center>



Distance
------------------------
.. |picdistance| image:: /images/distance.png
   :width: 50

|picdistance| **Distance Measurement Tool** 

This tool measures the tridimensional distance of the lines connecting a series of points. To start a measurement, click on the 
distance measurement icon and start clicking on the desired position (two or more). Right click to complete the measurement process. 
The unit of distance measurement is meter.

Further information such as total length can also be obtained from selecting this under the scene section in the sidebar.
All red points are draggable to adjust their positions.


.. raw:: html

  <center>
    <video controls src="../_static/Distance.mp4" width ="500" height="300"></video>
  </center>





Height
----------------------
.. |picheight| image:: /images/height.png
   :width: 50

|picheight| **Height Measurement Tool** 

This tool measures the vertical distance between two points. To start a measurement, click on the height measurement icon and 
then click on the desired two positions. The process will be automatically completed. More information can also be obtained from 
selecting this element under the scene section in the sidebar.

All red points are draggable to adjust their positions.

.. raw:: html

  <center>
    <video controls src="../_static/Height.mp4" width ="500" height="300"></video>
  </center>





Circle
-----------------
.. |piccircle| image:: /images/circle.png
   :width: 50

|piccircle| **Circle Measurement Tool** 

This tool measures the radius of a circle formed by three points. To start a measurement, click on the circle measurement icon 
and then click on three desired positions.The process will be automatically completed. All red points are draggable to adjust 
their positions.

More information such as Circumference can also be obtained from selecting this element under the scene section in the sidebar.

.. raw:: html

  <center>
    <video controls src="../_static/Circle.mp4" width ="500" height="300"></video>
  </center>



Remove 
-------------------------
.. |pictrash| image:: /images/trash.png
   :width: 50

|pictrash| **Remove all Measurements** 

To remove all measurements has been made, click on the trashbin icon or press "Escape".


Navigation
==================================
.. |picnavigation| image:: /images/navigationicon.png
   :width: 50

|picnavigation| **Navigation Modes**

The default navigation mode is Earth control. Potree viewer will always save the previous selected navigation mode as the default 
navigation mode when the viewer is loaded next time.


Earth Control
----------------------------------
.. |picearth| image:: /images/earth_controls_1.png
   :width: 50

|picearth| **Earth Control**

Earth control navigated as anchored to the pointcloud. Mouse left button pans the pointcloud, mouse wheel controls zoom, 
and right button orbits the pointcloud.

Pressing "Ctrl", key and holding the left mouse button changes the direction of the view.

.. raw:: html

  <center>
    <video controls src="../_static/earthcontrol.mp4" width ="500" height="300"></video>
  </center>

Fly control
----------------------------------
.. |picfly| image:: /images/fps_controls.png
   :width: 50

|picfly| **FLy Control**

Fly control moves the view as in a bird eyes using the keyboard. Keys "W" and "S" moves forward and backwards, respectively
and in the direction of the view, while "A" and "D" moves left and right respectively. 

Also, the "R" and "F" keys moves the view up and down. The mouse left button changes the direction of the view, mouse wheel
controls the speed for these movements and right button moves the view in the XYZ axis.

.. raw:: html

  <center>
    <video controls src="../_static/flycontrol.mp4" width ="500" height="300"></video>
  </center>

Screenshot
==================================
.. |picscreenshot| image:: /images/screenshot.png
   :width: 50

|picscreenshot| **Screenshot**

Screenshot icon is used to get a screen print and save it locally. It takes screenshots without any background, but contains 
the result of measurements.


Point Budget Slider
==================================
.. image:: /images/pointbudget_slider.png
   :height: 60
   :width: 400


The point budget limits the number of points loaded and rendered at any given time, which helps to adapt performance 
requirements to the capabilities of different hardware. It gives you a complete version of point clouds.

Potree viewer will save the previous selected point budget as the default point budget when the viewer is loaded next time.


.. raw:: html

  <center>
    <video controls src="../_static/Pointbudget.mp4" width ="500" height="300"></video>
  </center>


Display Options
==================================
.. image:: /images/corlorbutton.png
   :width: 200
   :height: 60

The display options button is a toggle button allows users to switch between RGB and Intensity modes.

RGB
----------------------------------

Display each point based on the object colors in 360 images.

.. image:: /images/corlored.png
   :width: 500
   :height: 300

Intensity
----------------------------------
Display each point based on the laser pulse return intensity value. Scanners identify an intensity value for each point during
the capture process. 
Intenisity is a measure of point reflectivity, which can vary depending upon color, surface texture,surface angle and the environment.

.. image:: /images/intensitied.png
   :width: 500
   :height: 300


360 Images
==================================
   
360 Imagess allow you to see actual 360 images of the point cloud. These images are displayed as white sphere in the viewr, 
click on any of them to enter in to it.   

To turn on/off 360 images,click the 360images toggle button.360 Images can add meaningful context to collected data and fill in the information lacking in the point cloud.

To exit from 360 images, click right upper corner exit button or press "Escape". 

Opacity slider changes the opacity of point cloud. This view will give you an overview on how the territory look like and what objects 
could be captured. 


.. raw:: html

  <center>
    <video controls src="../_static/360image.mp4" width ="500" height="300"></video>
  </center>

Keyboard Shortcuts
==================================

**Key P**
For selected pointcloud datasets, the animation will load automatically. Pressing "P" key will start / pause / resume the animation from current view position.
Use "Speed Slider" to adjust the animation speed.

**Key M**
Hit the "M" key to start screen recording. Then select the window that you want to record. To stop screen recording and save the video locally hit the "M" key again / click "Stop sharing". 