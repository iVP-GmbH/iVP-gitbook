# Reset Window Layout from outside iVP Planning

When iVP Planning is closed, your current window layout is saved and restored when you open the application the next time. Under rare conditions, Planning might save a layout that renders the application unusable (windows are configured in a way that prevents the user from interacting with the application). If this has happened to you, you can fix this by restoring the default window layout from outside the application. Do do so, follow below steps:

1. Make sure iVP Planning is closed

1. Open the Registry Editor

    You can do so by pressing the keyboard shortcut _Windows + R_, typing in _regedit_ in the small window that pops up on the bottom of your screen and pressing _Enter_ or clicking _Ok_.

1. Navigate to the iVP Planning directory

    You can find the iVP Planning directory in the panel on the left hand side under Computer > HKEY_CURRENT_USER > Software > iXtenda GmbH > iVP Planning. Or you can paste _Computer\HKEY_CURRENT_USER\Software\iXtenda GmbH\iVP Planning_ in the navigation bar at the top of the registry editor and press _Enter_.

1. Delete the registry key that saves the window layout

    Select the key with the name _09a679e2-1adc-4c7e-88f5-f93af3b8d771_h1211235444_, right click it and select _Delete_.

    ![](/.gitbook/assets/window-layout-regedit.png)

The next time you open iVP Planning your window layout will be restored to the default layout.