# DXF Files

In iVP it is possible to import and export DXF files, that function as a simplified 2d visualisation of 3d models. They can be useful for illustrating a planned layout.

After a DXF file is imported, it will be added to the [hierarchy](../user-interface/the-machine-list.md) and can be [edited](../machines/selecting-and-moving-objects.md) as any other object.

{% hint style="warning" %}
This is different to an [imported PDF](../getting-started/importing-pdfs.md), which will not be moveable in iVP but can be used as a overlay for the [floor plan](../user-interface/the-floor-plan.md).
{% endhint %}

{% hint style="info" %}
For better understanding and training we created a [<img src="../../../.gitbook/assets/YouTube_icon.png" alt="" data-size="line"> YouTube Tutorial](https://www.youtube.com/watch?v=Maxivv824Dk&list=PLlzoGkRUR67houzn5F5ejD3R-kQrDcps5&index=18), where you can find a detailed explanation how to import and export of DXF files.
{% endhint %}

## Importing a DXF File:

To import a DXF click **File -> DXF -> Import DXF**. 

![](../../../.gitbook/assets/DXF\_Import\_open.jpg)

A new window will open that allows to navigate to the folder containing the DXF file to be imported. To open the file, simply double click it **or** select it and click Open.

![](../../../.gitbook/assets/DXF\_Import\_file.jpg)

Before iVP Planning imports a DXF file, a prompt will ask to set some parameters that specify how the DXF file will be imported. 

![](../../../.gitbook/assets/DXF\_Import\_settings.jpg)

* _**File path:**_ this line represents the location of the to be imported file, change it by clicking the three dots
* _**As references:**_ this toggle defines whether or not you reference the dxf file. If checked, you will need to keep the dxf file accessible. (changing the name or location of that file will break the reference!) 
* _**Line width:**_ this value represents the width of each line (in mm)
* _**Scale:**_ this value represents the scale **of the DXF to import**, e.g. 1:1 or 16:1
* _**Unit:**_ this value represents the measurement unit **of the DXF to import**, e.g. mm, cm, inch...

![](../../../.gitbook/assets/DXF\_Import\_comparison.jpg)

{% hint style="info" %}
Note that the **scale** and the **measurement unit** for imported files refer to the scale/unit the DXF file was planned in and not the scale you want to use in your iVP Planning project. If changed in comparison to the origin; the size of the import might be incorrect.
{% endhint %}

## Exporting a DXF File:

To export objects from iVP Planning, first select the ojects you want to export.

![](../../../.gitbook/assets/DXF\_Export\_selection.jpg)

Then click **File -> DXF -> Export Selection**.

![](../../../.gitbook/assets/DXF\_Export\_open.jpg)

A new window will open that allows to choose a location for the exported file.

![](../../../.gitbook/assets/DXF\_Export\_file.jpg)

Before iVP Planning exports a DXF file, a prompt will ask to set some parameters that specify how the DXF file will be exported. 

![](../../../.gitbook/assets/DXF\_Export\_settings.jpg)


* _**File path:**_ this line represents the target location of the file, change it by clicking the three dots
* _**Unit:**_ this value represents the measurement unit **of the DXF to export**, e.g. mm, cm, inch...
* _**Side:**_ this represents the viewing direction the file will be created from (Overhead View, Side View right, Front View)

## Coloring DXF Files:

To export colored lines in a DXF file, the **selected objects** need to be [colored] first(../machines/highlighting-objects.md). After exporting the file any import will show the changed object outlines in this color.

{% hint style="info" %}
[Colored Objects](../machines/highlighting-objects.md) will **not show up as colored** in the [3d view](../user-interface/the-3d-panel.md).
{% endhint %}

## Troubleshooting
Although iVP can process most DXF files and versions, some issues might arise. 
### Old DXF versions
Unfortunately it is not possible to process all existing DXF versions to work with iVP. This might be, because the program used to create the DXF file uses a really old standard (1995 or older).
### Text support 
Not all fonts are supported for DXF Import. Also some forms of alignments (vertical text, justificated text, e.g.) can not be converted and might be imported incorrectly. A workaround is to import without text and use our text object to add text information. Alternatively you can use iVP Plannings font in your file (Roboto Regular).
### Round Contures
Round contures might be imported incomplete or fractured, as the import utilizes only lines and therefore might break up a round conture.  
{% endhint %}
