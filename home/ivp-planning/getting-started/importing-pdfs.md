# Importing PDFs

In iVP it is possible to import PDFs that will act as an overlay for the [floor plan](../user-interface/the-floor-plan.md). This can be useful for illustration or when it is necessary to transform a 2D (factory) plan into a 3D scene.


{% embed url="https://youtu.be/MuLt94b64O8?t=203" %}
How to import and export PDFs (german)
{% endembed %}

## Importing PDFs step by step:

To import a PDF click on **File -> PDF -> Import PDF**. A new window will open that allows you to navigate to the folder that contains the PDF you want to import.

![](../../../.gitbook/assets/iVP\_pdf\_import\_pfd\_menu\_entry.jpg)

As soon as you found the file, simply double click or it or select it and click **Open**.

![](../../../.gitbook/assets/iVP\_pdf\_import\_pdf\_file\_dialogue.jpg)

Before iVP actually processes PDF and imports it, you will be asked to set some parameters that specify it will be loaded. The options are:

* _**PPI:**_** t**his value represents the resolution of the PDF to import (most PDFs have a default resolution of 72 PPI so it is usually not necessary to change this value)
* _**Scale:**_ this value represents the scale of the PDF to import, e.g. 1:100 or 1:50
* _**Resize floor to PDF scale:**_ if checked the size of the floor plan will be adjusted to be equal to the dimensions of the imported PDF
* _**Transparent background:** i_f checked the usually white background of the imported PDF will be removed so that only its contents are visible

{% hint style="info" %}
PDF PPI and PDF scale are interdependent values. Therefore the PPI value can also be used to compensate an incorrect PDF scale. However, it is usually not necessary to change the PPI value.
{% endhint %}

![](../../../.gitbook/assets/iVP\_pdf\_import\_pdf\_options.jpg)
