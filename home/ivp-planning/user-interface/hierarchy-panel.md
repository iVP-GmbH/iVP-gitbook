---
title: Hierarchy Panel
description: >-
  The Hierarchy panel displays the main structure of your project's setup by providing you a tree view of all the objects your project currently contains. It can help you organizing your project's complexity and keeping an overview of your currently used assets.
---

![Hierarchy Panel](../../../.gitbook/assets/Hierarchy.jpg)

Every object that is added to a project will get an associated entry in the hierarchy panel during its creation. It is possible to collect objects in [folders](#folders), to [rename](../machines/renaming-objects-and-folders.md) objects and folders, to toggle their [visibility](#hide-unhide-objects) or to [lock](#lock-unlock-objects) them to prevent unwanted changes.

## The elements of the panel

|     |     |
| --- | --- |
| ![Hierarchy Search Bar](../../../.gitbook/assets/planning_hierarchy_panel_search.png) | The __Search Bar__ makes it possible to filter machines or objects inside the hierarchy by name. The search is not case sensitive. |
| ![Hierarchy New Folder](../../../.gitbook/assets/planning_hierarchy_panel_new_folder.png) | __New Folder__ adds a new folder to the hierarchy. |
| ![Hierarchy Color](../../../.gitbook/assets/planning_hierarchy_panel_color.png) | __Color__ provides you an indicator of the [color](../machines/highlighting-objects.md) set for the object(s) via the [Colorize](../machines/highlighting-objects.md) tool of the 2D View. |
| ![Hierarchy Lock/Unlock Machine](../../../.gitbook/assets/planning_hierarchy_panel_lock_unlock_machine.png) | __Lock/Unlock Machine__ lets you lock or unlock the currently selected object(s) for editing. |
| ![Hierarchy Hide/Unhide Machine](../../../.gitbook/assets/planning_hierarchy_panel_hide_unhide_machine.png) | __Hide/Unhide Machine__ toggles the visibility of the currently selected object(s) in the 2D View and 3D View. |

## Folders

Folders can be used to optimize the structure of your project by grouping the objects you placed inside. They will be treated as a single parent object that can be colorized, locked or hidden as well. Locking and Hiding them will also affect all children objects inside - in the [2D View](../user-interface/the-2d-panel.md) and in the [3D View](../user-interface/the-3d-view.md).

{% hint style="info" %}
Folders can only be accessed in the hierarchy panel.
{% endhint %}

### Creating folders

![](../../../.gitbook/assets/planning_hierarchy_new_folder.png)

To create a folder click on the ![Hierarchy New Folder](../../../.gitbook/assets/planning_hierarchy_panel_new_folder_small.png) __New Folder__ button in the top right corner of the hierarchy panel. A new folder will be added to your hierarchy.

{% hint style="info" %}
The new folder will be placed at the bottom position of the current hierarchy. It can then be sorted into/under other folders or objects. 
{% endhint %}

## Moving objects in the hierarchy panel

Objects can be [moved](../machines/select-objects.md#selecting-objects-via-the-hierarchy) in the hierarchy via drag and drop. A white frame will indicate where the object will be placed. Drop an object onto another one to group it together with the target.

| __Drag__ | __Drop__ |
| --- | --- |
| ![Hierarchy Move Drag](../../../.gitbook/assets/planning_hierarchy_moving_objects_drag.png) | ![Hierarchy Move Drop](../../../.gitbook/assets/planning_hierarchy_moving_objects_drop.png) |

## Lock/Unlock objects

To prevent objects from being [selected](../machines/select-objects.md#selecting-objects-in-the-2d--and-3d-panel) and [moved](../machines/move-objects.md) in the [2D View](the-2d-panel.md) and [3D View](the-3d-view.md) press the ![Hierarchy Lock](../../../.gitbook/assets/planning_hierarchy_panel_lock_unlock_machine_small.png) **Lock/Unlock Machine** button.

## Hide/unhide objects

To hide or show one or more objects [select](../machines/select-objects.md#selecting-objects-via-the-hierarchy) them and press the ![Hierarchy Visibility](../../../.gitbook/assets/planning_hierarchy_panel_hide_unhide_machine_small.png) **Hide/Unhide Machine** button.

A hidden object will not be shown in the [2D View](the-2d-panel.md) and [3D View](the-3d-view.md). It will still be shown in the Hierarchy Panel with a darker grey color and the ![Hierarchy Hidden Object](../../../.gitbook/assets/planning_hierarchy_panel_hidden_object_small.png) icon. You can still edit it in the [Properties Panel](./the-properties-panel.md).

![Hierarchy Hidden Object](../../../.gitbook/assets/planning_hierarchy_hidden_object.png)

{% hint style="warning" %}
You can __not__ [__move__](../machines/move-objects.md) or [__rotate__](../machines/rotate-objects.md) a hidden object in the [2D View](the-2d-panel.md) and [3D View](the-3d-view.md).
{% endhint %}

## Context Menu

You can open a context menu for any object with a __Right Click__ on it inside the Hierarchy Panel.
Next to the already mentioned options to [colorize](#the-elements-of-the-panel), [lock](#lock-unlock-objects) and [hide](#hide-unhide-objects) there are additional features available for you.

![Hierarchy Context Menu](../../../.gitbook/assets/planning_hierarchy_context_menu.png)

__Rename__ allows you to edit the name of the object.

__Copy__ lets you copy the object (without its children).

__Delete__ will remove the currently selected object(s).

__Select Children__ allows you to select the object and its children.

__Create folder from selection__ will create a new folder with the currently selected objects inside of it.

__Mirror__ allows you to mirror the currently selected object(s) horizontally or vertically.

__Reset Scale__ will set the [scale](../machines/scale-objects.md) value of the currently selected object(s) to its default values (usually 1 on all axes).