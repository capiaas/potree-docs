
Appearance
++++++++++++++

Point Budget
==================================

The point budget limits the number of points loaded and rendered at any given time, which helps to adapt performance requirements to the capabilities of different hardware. It gives you a complete version of point clouds.

Recommended values are between 500.000 and 10.000.000.

 
Field of View
==================================

To control model elements to be included within the scene, the field of view can be adjusted. Default value is set to 55 degrees.
The field of view will determine how much of the model you can see in your screen.

.. raw:: html

  <center>
    <video controls src="../_static/Pointbudget.mp4" width ="500" height="300"></video>
  </center>


Eye Dome-lighting
==================================

The Potree Point Cloud 3d viewer module can implement eye dome-lighting, a lighting model that highlights the shapes of objects.

Eye Dome-lighting group objects, shade their outlines and enhances depth perception in scientific visualization images. 

It is useful for recognition and measurement of structures within a model. It can be modified by adjusting Radius, Strength, and Opacity.Those are set to give you tight controls of movement with in the model.

By default, Eye Dome-Lighting is enabled on Potree 3D viewer, but it can be disabled by clicking on the enable option.


.. raw:: html

  <center>
    <video controls src="../_static/Eyedom_lightning.mp4" width ="500" height="300"></video>
  </center>


Background
==================================

Potree 3D viewed background can be modified with following available options:

*  Street Map
*  Skybox
*  Gradient
*  Black and white

.. raw:: html

  <center>
    <video controls src="../_static/Back_ground.mp4" width ="500" height="300"></video>
  </center>



Splat Quality 
==================================
Splat quality can be adjusted to standard or high quality, to improve the appearance of the model.

High quality will give you the best viewing experience on your computer. if you are on a smart phone, you can 
keep the settings at standard quality. It may be a good idea to move the point budget down to about 5 million to keep 
your phone running smoothly.

*Min node size - impacts the point density of the nodes represented*.

*Box - Displays the boxes of the nodes*.

*Lock view - Lock the point cloud view, preventing to load or unload points to the model*.


.. raw:: html

  <center>
    <video controls src="../_static/Splat_quality.mp4" width ="500" height="300"></video>
  </center>
