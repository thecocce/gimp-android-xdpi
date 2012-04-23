gimp-android-xdpi
=================

Gimp plugin to export images or icons for all android densities. Just select the area to export, then run the plugin
from Filters/Android/Write Android XDPIs... Images will be written to your drawable-ldpi / mdpi / hdpi / xhdpi folders.
You can select a custom target width so you don't have to resize your picture.

To write you app icon directly from you full size picture, use these parameters : 
 1. select your app res folder
 2. type `icon` as the image base name
 3. select a image width of `48`
 4. select a density of `mdpi`
 5. select image format `png`

Icon or Image resources for all densities will be scaled and written accordingly.
You will be warned if an image has been upscaled

### Installation: 
* Put this file into your gimp plugin directory, ie: ~/.gimp-2.6/plug-ins/gimpfu_android_xdpi.py
* Restart Gimp
* Run script via Filters/Android/Write Android XDPIs...
