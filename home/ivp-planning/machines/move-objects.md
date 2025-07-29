# Move Objects

In iVP, objects always have a position in the three dimensional space. This position can be changed by moving objects around.

{% embed url="https://youtu.be/7Vprataxi08?t=87" %}
How to select and move objects (german)
{% endembed %}

## Moving objects in the 2D View:

In the [2D View](../user-interface/the-2d-view.md), objects can be moved by using the handle that appears as soon as an object is selected. To move the object unrestricted by **dragging the circle** in the middle of the handle. To move the object along a specific axis **drag the arrow** of the respective direction.

![](../../../.gitbook/assets/iVP_Planning_ObjectInteraction_2DMoveObjects.png)

## Moving objects in the 3D View:

To move an object in the [3D View](../user-interface/the-3d-view.md) first make sure that you activated the **move mode** by clicking on the respective button of the [3D View toolbar](../user-interface/the-3d-view.md#the-toolbar-of-the-3D View).

![](../../../.gitbook/assets/iVP_Planning_ObjectInteraction_3DMoveObjects.png)

As soon as you are in the move mode, the handle in the center of the object will change to an angle bracket with three axis which have small arrows at the ends. By **dragging an arrow with the mouse** the object will move in the respective direction. To **drag the cube** in the center results in a free movement of the object.

## Moving objects via the properties panel:

It is possible to move an object via **text input** in the [properties panel](../user-interface/the-properties-panel.md). The numbers entered in the fields define where the object is located in the scene.

{% hint style="info" %}
The position values in the properties panel always equal the distance of the object to the current [reference point](../user-interface/the-grid.md) of the [coordinate system](../user-interface/the-grid.md). If the reference point changes, the position values in the properties panel will change accordingly. However, this change does not affect the actual position of the object in the scene.
{% endhint %}

![](../../../.gitbook/assets/iVP_Planning_ObjectInteraction_PropertiesMoveObjects.png)