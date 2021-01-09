# Coreboot Bootsplashes
This is just a place to store some of my custom [coreboot](https://github.com/coreboot/coreboot) bootsplashes.
All bootsplashes are 1024x768 16 bits RGB bitmap files (.bmp) and tested with SeaBIOS payload.

# Naming scheme
 - Any file with "**43**" in the name is a 4:3 image.
 - Files with "**169**" *or* do not have an identifier are 16:9 images.
 - *16:9 images have assets that have their horizontal scaling
   divided by 1.33 to look correct when expanded to a 16:9 image.*
- Any file with "**(Prev)**" in the name is a preview file for your convenience.
- The actual bootsplash files are compressed and ready to insert into your coreboot rom.

# Previews
- 4:3 preview images are scaled to 1400x1040.
- 16:9 preview images are scaled to 1600x900.

This allows you to see how the images should look when actually incorporated into the CBFS. I chose these settings as it should be the lowest common denominator for (IBM/Lenovo) laptops, I do not expect everyone to have the highest possible screen resolutions.
