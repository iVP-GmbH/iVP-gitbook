# Markup Tool

The markup tool is an easy bto use function of iVP that can be used to anutate issues or highlights inside your project and commnicate better with colleages or clients.

{% hint style="info" %}
For better understanding and training we created a ![](../../../.gitbook/assets/YouTube\_icon.png) [iVP YouTube Channel](https://www.youtube.com/watch?v=DYKIYcZMrVE&list=PLlzoGkRUR67houzn5F5ejD3R-kQrDcps5&index=16) where you can find tua detailed tutorial for the markup tool.
{% endhint %}


## Placement:

The markup tool can be activated by clicking the markup icon in the [2D-panel toolbar](../user-interface/the-2d-panel.md#the-toolbar-of-the-2d-panel).

![](../../../.gitbook/assets/markup\_icon.jpg)

As soon as the tool is active, the icon will turn a small markup icon will follow the mouse cursor to remind you that you are in the markup mode.

![](../../../.gitbook/assets/markup\_cursor.jpg)

To create a markup, **left click on a position** in the [2D-panel](../user-interface/the-2d-panel.md) or [3D-panel](../user-interface/the-3d-panel.md). A blue markup (a pin resembling a map location marker) will appear that marks the spot where you clicked and functions as an interactable highlight point.

![](../../../.gitbook/assets/markup\_placement.jpg)

The placed markup will be added to the [hierarchy](../user-interface/the-machine-list.md) and can be used as any other object. It can be [renamed and grouped in folders](../the-tree-view/renaming-objects-and-folders.md), [set in/visible](../the-tree-view/visibility-of-objects-and-folders.md), set to be [un/locked](../the-tree-view/locked-objects-and-folders.md) and [recolored](../machines/highlighting-objects.md).

## Editing a Markup:

After placing a markup, the [properties panel](../user-interface/the-info-panel.md) will show the default options to [move an object](../machines/move-objects#moving-objects-via-the-info-panel.md) and most foremost a section to edit the selected markup.

![](../../../.gitbook/assets/markup\_properties.jpg)

## The default fields:

* _**Name:**_ the name of the object which [can be changed](../the-tree-view/renaming-objects-and-folders.md) at any time
* _**ID:**_ the unique ID of the object which is generated when the markup is [placed](../machines/first-steps-with-3d-object.md) in the [2D-](../user-interface/the-2d-panel.md) or [3D-panel](../user-interface/the-3d-panel.md); the ID is unchangeable 
* _**Author:**_ the author of the markup, per default "Planner"; this information is unchangeable and independent from the object name
* _**Created:**_ exact time and date when the markup was created; this information is unchangeable
* _**Transform:**_ the panel containing information of the markup regarding

    * _**Dimensions:**_ the dimensions of the object; this information is only changeable by changing the [scale](../machines/scale-objects.md)
    * _**Position:**_ the position of the object, changing this will [move the object](../machines/move-objects#moving-objects-via-the-info-panel.md)
    * _**Scale:**_ the [scale](../machines/scale-objects.md) of the object; use with caution!
    * _**Rotation:**_ the [rotation](../machines/scale-and-rotate-objects.md) of the object

* _**Markup:**_ the panel containing information about the markup regarding
   
    * _**Priority:**_ a Priority can be set for each individual markup, which helps with sorting markups in the [markups panel](../ivp-planning/user-interface/markups-panel.md) and works great if combined with [recoloring](../machines/highlighting-objects.md)
        * _**Low:**_ set the priority of the selected markup to low
        * _**Medium:**_ Set the priority of the selected markup to medium (default)
        * _**High:**_ set the priority of the selected markup to high
    * _**Status:**_ the status of a markup can be set and this information will be reflected in the [markups panel](../user-interface/markups-panel.md).
        * _**Open:**_ Set the status of the selected markup to open (default)
        * _**Closed:**_ set the status of the selected markup to closed
    * _**Description:**_ the description of the selected markup

## Conversation with Markups:

In addition to the description of a markup, it is possible to **add information to a markup without creating a new one**. To do so, you can use the [conversation panel](../user-interface/conversation-pane.md)
![](../../../.gitbook/assets/conversation\_panel.jpg)

## Using the Conversation Panel:

|                                                                           |                                                                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](../../../.gitbook/assets/conversation\_panel\_reply.jpg)                      | Input field for text to be shown in the conversation below
|
| ![](../../../.gitbook/assets/conversation\_panel\_send\_text.jpg)                 | sends text to be shown in conversation below (alternativly press **Enter** in the input field ) 
|
| ![](../../../.gitbook/assets/conversation\_panel\_create\_screenshot.jpg)         | replaces the [3d-view](..user-interface/the-3d-panel.md) with a panel that lets you [take and edit screenshots](/markup-tool.md#taking-a-screenshot-in-conversations)
|
| ![](../../../.gitbook/assets/conversation\_panel\_delete.jpg)                     | after sending a text it will be shown like in a chat with date/time of the text and who posted it; to delete a text, click the small bin icon
|
| ![](../../../.gitbook/assets/conversation\_panel\_screenshot.jpg)                 | after [creating a screenshot](#taking-a-screenshot-in-conversations) it will be shown with the date and time it was posted; to delete a screenshot from the conversation, click the small bin icon
|
| ![](../../../.gitbook/assets/conversation\_panel\_screenshot\_reply.jpg)          | reopens the panel to [create a screenshot](#taking-a-screenshot-in-conversations) and will post a new screenshot in the conversation after confirming
|

## Taking a screenshot in Conversations

After you press the Button **Create Screenshot**, the [3d-view](..user-interface/the-3d-panel.md) will be replaced with a panel that offers the possibility to take and edit screenshots.

![](../../../.gitbook/assets/markup\_screenshot\_panel.jpg)

You can use the 3d-view to [change the content of the screenshot](../getting-started/moving-the-camera.md) until it fits your need.

![](../../../.gitbook/assets/markup\_screenshot\_panel\_buttons.jpg)

When you are ready to take the screenshot, you have the option to confirm or cancel the screenshot. To do so, use **the buttons in the upper right corner of the screenshot**.

![](../../../.gitbook/assets/markup\_screenshot\_panel\marking\_bar.jpg)

|                                                                           |                                                                                                                                                                                                                                                                                                              |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_color.jpg)        | change the color of the brush
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_brush.jpg)        | use a brush to scribble directly onto the screenshot; change the size of the brush by clicking the small triangle in the corner 
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\eraser.jpg)        | use a eraser to delete scribbles on the screenshot; change the size of the eraser by clicking the small triangle in the corner
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_clear.jpg)        | delete all scribbles on the screenshot; does not delete the screenshot itself!
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_undo.jpg)         | undo the last action (painting or erasing), or redo the last action
|
| ![](../../../.gitbook/assets/markup\_screenshot\_panel\_confirm.jpg)      | confirm the screenshot and send it to the conversation, or cancel the screenshot 
|