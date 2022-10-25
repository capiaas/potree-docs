
Appearance
++++++++++++++

Point Budget
==================================

The point budget limits the number of points loaded and rendered at any given time, which helps to adapt performance requirements to the capabilities of different hardware. Recommended values are between 500.000 and 10.000.000.
   


Field of View
==================================

To control model elements to be included within the scene the field of view can be adjusted. Default value is set to 55 degrees.

.. image:: /images/pointbudget.png

Eye Dome-lighting
==================================

The Potree Point Cloud 3d viewer module can implement eye dome-lighting, a lighting model that highlights the shapes of objects.

Eye Dome-lighting group objects, shade their outlines and enhances depth perception in scientific visualization images. 

It is useful for recognition and measurement of structures within a model. It can be modified by adjusting Radius, Strength, and Opacity.
By default, Eye Dome-Lighting is enabled on Potree 3D viewer, but it can be disabled by clicking on the enable option.

Background
==================================

Potree 3D viewed background can be modified with following available options:

*  Street Map
*  Skybox
*  Gradient
*  Black and white


Splat Quality 
==================================
Splat quality can be adjusted to standard or high quality, to improve the appearance of the model.
Min node size - impacts the point density of the nodes represented.
Box - Displays the boxes of the nodes.
Lock view - Lock the point cloud view, preventing to load or unload points to the model.

