# Fence Tool

The fence tool can be used to quickly generate fences without the need to work with single fence elements or manual corrections after course changes.

{% hint style="info" %}
The fence tool is a special variant of the [path tool](path-tool.md). We recommend to read the [path tool ](path-tool.md)section of this manual first.
{% endhint %}

## Creating a fence:

Fences are based on measurements which can be created with the [path tool](path-tool.md). Afterwards, every path can be turned into a fence by **changing the 'Type' into Fence** that is displayed in 'Measurements' as soon as a path is [selected](path-tool.md#path-selection-and-editing).

![](../../../.gitbook/assets/iVP\_fence\_tool\_create\_fence.jpg)

Alternatively, it is possible to **right click** on the desired path, followed by a **click on "Fence"**. This will convert the path into a fence as well.

![](../../../.gitbook/assets/iVP\_fence\_tool\_right\_click\_menu\_to\_fence.jpg)

Fences can be identified by the fence icon that is displayed next to their name.

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_icon.jpg)

## Editing the fence course:

The course of a fence can be changed by [editing the path](path-tool.md#path-selection-and-editing) the fence is based on. After length or direction changes the fence model will automatically be adjusted to the new course.

## Doors and pass-troughs:

It is possible to add doors or pass-troughs to fences which will automatically be adapted when the fence changes in length or direction. To add one, right **click on a path point** of a selected path in the [2D-panel](../user-interface/the-2d-panel.md) and choose **"Door"** or **"Pass-through"** from the appearing menu.

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_right\_click\_point\_options.jpg)

Doors are always placed on the right side of the path point and have a fixed width.

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_door.jpg)

Pass-troughs have a flexible width, they always span from the selected point to the next point on its right side.

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_passthrough.jpg)

## Fence types and materials:

It is possible to change the type respectively material of the fence. To do so, **choose an option from the list**.

![](../../../.gitbook/assets/iVP\_fence\_tool\_create\_fence.jpg)

![](../../../.gitbook/assets/iVP\_fence\_tool\_fence\_types.jpg)
