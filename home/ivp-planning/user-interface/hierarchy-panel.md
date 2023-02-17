# Hierarchy Panel

Every object that is added to a project will get an associated entry in the hierarchy panel during its creation. This panel contains a list of all machines, objects, [markups](../advanced-tools/markup-tool.md), images, [DXF imports](../advanced-tools/dxf-tool.md), [PDF imports](../getting-started/importing-pdfs.md) and [virtual cameras](../advanced-tools/virtual-cameras.md) and is used to organize them in a tree structure. 

Via this panel it is possible to collect objects in [folders](#folders), to [rename](../machines/renaming-objects-and-folders.md) objects and folders, to toggle their [visibility](#visibility) or to lock them to prevent unwanted changes.

![](../../../.gitbook/assets/hierarchy.jpg)

## The elements of the panel:

|                                                           |                                                                                                                                                   |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](../../../.gitbook/assets/Hierarchy_search.jpg)        | The search bar makes it possible to only display such machines or objects which names contain the entered text (the search is not case sensitive) |
| ![](../../../.gitbook/assets/Hierarchy_folder_button.jpg) | Adds a new folder to the hierarchy                                                                                                                |
| ![](../../../.gitbook/assets/Hierarchy_color.jpg)         | Visualisation of the [color](../machines/highlighting-objects.md) set for the object(s)                                                           |
| ![](../../../.gitbook/assets/Hierarchy_lock.jpg)          | Locks or unlocks the currently selected object(s)                                                                                                 |
| ![](../../../.gitbook/assets/Hierarchy_visibility.jpg)    | Toggles the visibility of the currently selected object(s)                                                                                        |

## Folders

Folders can be used to structure projects. They can only be accessed in the hierarchy panel, however locking or hiding them will affect all objects inside - also in the [2D- ](../user-interface/the-2d-panel.md)and [3D-panel](../user-interface/the-3d-panel.md).

### Creating folders:

To create a folder, **press the "new folder" button** in the top of the hierarchy panel and a new folder will be added.

![](../../../.gitbook/assets/Hierarchy_new_folder.jpg)

{% hint style="info" %}
The new folder will be placed at the topmost position of the hierarchy. It can then be sorted into/under other folders or objects. 
{% endhint %}

### Moving objects in the hierarchy panel:

Objects can be [moved](../machines/selecting-and-moving-objects.md#selecting-objects-via-the-hierarchy-panel) in the hierarchy with drag and drop. A white frame will indicate where the object will go. Drop an object onto another one, to group it together with the target.
![](../../../.gitbook/assets/Hierarchy_move.jpg)

## Lock/unlock objects

To prevent objects from being [selected and moved](../machines/selecting-and-moving-objects.md#selecting-objects-in-the-2d--and-3d-panel) in the [2D](the-2d-panel.md) and [3D view](the-3d-panel.md) and  press the <img src="../../../.gitbook/assets/Hierarchy_lock.jpg" alt="" data-size="line"> **Lock/Unlock Machine** button.

Alternatively **right click** a selected object to open the context menu and lock the selected object(s).

![](../../../.gitbook/assets/Hierarchy_context_lock.jpg)

{% hint style="info" %}
Locked objects can still be edited in the hierarchy panel. 
{% endhint %}

## Hide/unhide objects

To hide or show one or more objects, [select](../machines/selecting-and-moving-objects.md#selecting-objects-via-the-hierarchy-panel) them and press the <img src="../../../.gitbook/assets/Hierarchy_visibility.jpg" alt="" data-size="line"> **Hide/Unhide Machine** button.

Alternatively you can right click a selected object and use the context menu to change the visibility of any selected object.

![](../../../.gitbook/assets/Hierarchy_context_visibility.jpg)

A hidden object will not be shown in the [2D view](the-2d-panel.md) and [3D view](the-3d-panel.md). It will still be shown in the hierarchy panel and turn to a darker grey color. It will still be editable in the hierarchy. 

![](../../../.gitbook/assets/Hierarchy_hidden_object.jpg)

{% hint style="warning" %}
A hidden object can **not be moved** in the [2D view](the-2d-panel.md) and [3D view](the-3d-panel.md)! 
{% endhint %}