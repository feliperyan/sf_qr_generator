Javascript generated QR Code for the current URL
==================================================

Javascript generated QR Code for the current URL - no external call necessary.

Ideal for when you need a QR Code created immediately after you create an object (such as an Asset) - the value of the QR Code is the complete URL for that object.

**HOW TO USE:**

1. If you don't plan to use this with the standard Asset object remember to edit the VisualForce page "QRCodeForCurrentURL.vfp" and modify --> standardController="Your_Object_Here"

2. Add a section to the object's layout, call it QR Code or something similar.
    * One Column
    * Un-tick Edit Page

3. Drag and drop the visualforce page to the section

4. Click on Properties for the VF Page element: Height = 300 pixels.