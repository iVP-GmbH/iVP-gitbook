# Loading Projects

In iVP you can load previously [Saved Projects](saving-projects.md) for continuous work or collaboration. 

## Loading projects step by step:

To load a project first click on **File -> Open**. A new window will open where you can navigate to the folder that contains the project file you want to load.

![](../../../.gitbook/assets/open_file_menu.jpg)
As soon as you found the file, simply double click or it or select it and click **Open**.

{% hint style="info" %}
Project files can easily be identified by their **.plan** extension. You can move them to other folders or share them with collogues or customers, but you should not remove or change their extension.
{% endhint %}

![](../../../.gitbook/assets/open_file_dialogue.jpg)
Before iVP actually processes the data from the file you will be asked to set some parameters that specify how the data will be loaded. The options are:

* _**Replace current scene**_**:** if checked iVP will replace the current project with the one stored in the save file

* _**Include PDF if available**_**:** if checked iVP will import the [floor plan](../user-interface/the-floor-plan.md) stored in the save file (if there is one). _This is a legacy option for old save files and might not be applicable to your .plan-file._

* _**Resize floor to saved dimensions:**_ adjusts the current [floor size](../user-interface/the-floor-plan.md#floor-plan-size) to the floor size stored in the save file

{% hint style="danger" %}
Please note that while replacing a scene or loading a PDF floor plan when another plan is already in the scene can result in the deletion of the old scene content or the previously used PDF, existing plan files remain untouched. However, there is a risk of losing unsaved progress in the process.
{% endhint %}

![](../../../.gitbook/assets/open_file_options.jpg)