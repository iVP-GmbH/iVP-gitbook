# Scaling

Scaling is one of the advanced tools iVP Planning provides. It allows resizing objects and machines, even if there is no specific object customization available.

There are different ways to scale a machine or object in iVP Planning:

## Scaling in 3D
One way to adjust an object's size is the scaling mode in the 3D view. Select the scaling icon and drag the handles displayed at the object center to scale it. 
The immediate visualization is perfect for fast approximate adjustments.

## Scaling in the object properties
An object can also be scaled using the input fields in the property window. To do so, select the object you want to edit and unfold the transform section if necessary.
{% hint style="info" %}
**Please notice:** The number set in the input field is a multiplier for the object's size. 
{% endhint %}

## Mirroring
Mirroring also affects the scale of an object. The mathematical sign of the scale multiplicator determines the orientation of the object. If the sign is negative, the object is mirrored.
You can mirror an object using the corresponding buttons in the 2D view or the context menu.

## Inherited scaling
The size of an object also changes when the scale of the parent is changed. In this case, the scale of the child object stays unchanged in the properties window. 

{% hint style="warning" %}
## Typical errors
The scaling of machines is to be used with care because it can lead to unpredicted behavior or produce errors. 

### Wrong machine dimension
Changing a machine's size by scaling can lead to wrong machine dimensions. Such a machine won't match the dimensions of the original.

### Skewing
Rotating a child of a scaled object leads to an effect called skewing. This behavior is no error, but the affected object will be deformed.

### Scaling distances
When a parent is scaled, the distance between this object will increase or decrease depending on the scale multiplier. 
{% endhint %}