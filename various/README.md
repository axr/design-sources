These images are for the AXR Browser Disk Image background.

The images at 1x and 2x scale should be 72 and 144 dpi, respectively.

The multi-resolution TIFF file which is actually used in the DMG can be generated from the source images as follows:

`tiffutil -cathidpicheck dmg-background.png dmg-background@2x.png -out dmg-background.tiff`