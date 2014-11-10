# Sklejar #

**sklejar** - this script joins [Compass](http://compass.krakow.pl) Trekbuddy 
maps' tiles into one big image. Result file can be loaded into
[OziExplorer](http://www.oziexplorer3.com) in order to draw an accurate route
which could be exported as GPX file

**Keep in mind that this is still under construction and is not fully working!**

## How to use ##

Simply `git clone` this repo and copy your Trekbuddy Compass maps into **maps**
dir so the dir layout looks like:

    .
    └── maps
        └── beskid_slaski
            ├── beskid_slaski.set
            └── set
                ├── BesSlaski_14_0_0.png
                ├── BesSlaski_14_0_1024.png
                ├── BesSlaski_14_0_1280.png
                ├── BesSlaski_14_0_1536.png
                ├── BesSlaski_14_0_1792.png
                ├── BesSlaski_14_0_2048.png
                ├── BesSlaski_14_0_2304.png
                ├── BesSlaski_14_0_2560.png
                ├── ... and many other image files
     
Just **make sure** that map directory name (**beskid_slaski** in the above example) 
is the same name as the **set** file in this directory: **beskid_slaski/beskid_slaski.set**
This file contains info about all tile images files that will be joined into the
one image file.
