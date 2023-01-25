# Loading Projects

In iVP you can load previously [Saved Projects](saving-projects.md) for continuous work or collaboration. We would recommend to have a look at this [<img src="../../../.gitbook/assets/YouTube_icon.png" alt="" data-size="line"> YouTube Tutorial](https://youtu.be/MuLt94b64O8) for a quick introduction.

## Loading projects step by step:

To load a project first click on **File -> Open**. A new window will open where you can navigate to the folder that contains the project file you want to load.

![](../../../.gitbook/assets/iVP\_open\_file\_menu\_entry.jpg)

As soon as you found the file, simply double click or it or select it and click **Open**.

{% hint style="info" %}
Project files can easily be identified by their **.hfc** extension. You can move them to other folders or share them with collogues or customers, but you should not remove or change their extension.
{% endhint %}

![](../../../.gitbook/assets/iVP\_open\_file\_dialogue.jpg)

Before iVP actually processes the data from the file you will be asked to set some parameters that specify how the data will be loaded. The options are:

* _**Replace current scene**_**:** if checked iVP will replace the current project with the one stored in the save file
* _**Include PDF if available**_**:** if checked iVP will import the [floor plan](../user-interface/the-floor-plan.md) stored in the save file (if there is one)
* _**Resize floor to saved dimensions:**_\*\* \*\* adjusts the current [floor size](../user-interface/the-floor-plan.md#floor-plan-size) to the floor size stored in the save file
* _**Apply highlight colors**_**:** loads and applies [colorings ](../machines/highlighting-objects.md)stored in the save file to specific machines or objects

{% hint style="danger" %}
To replace a scene or to load a PDF floor plan when another plan is already in the scene will lead to the deletion of the old scene content or the previously used PDF. This deletion is permanent.
{% endhint %}

![](../../../.gitbook/assets/iVP\_open\_file\_options.jpg)

If your local iVP installation does not have access to the same [databases ](broken-reference)that were used to create the save file, it is possible to replace missing machines and objects with placeholders. Otherwise it is possible to [import the missing database](broken-reference).
