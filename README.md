### A collection of overlays and bootlogos for Knulli
<img width="3468" height="867" alt="Knulli_banner" src="https://github.com/user-attachments/assets/8760b795-e603-411a-ac46-bd5d0b322ea4" />


Note that image scaling can affect the apparent unevenness of gridlines in the examples below (for example, all of the 720x720 grids are integer scale but may not appear that way in the image previews). Click the images to see the full-sized versions.
# [Overlays](https://github.com/mugwomp93/Knulli_Customization/tree/main/overlays)

Most of these [overlays](https://github.com/mugwomp93/Knulli_Customization/tree/main/overlays) can be found in my [other](https://github.com/mugwomp93/muOS_Customization) [repositories](https://github.com/mugwomp93/720x720_overlays), but the versions here have been configured for use with the Knulli frontend (i.e., no messing with Retroarch). Due to the logic Knulli uses to select overlays and the associated naming conventions, I've divided my overlays into four mutually exclusive decoration sets (integer scale with grids, integer scale without grids, non-integer scale with grids, non-integer scale without grids). Just download the zip(s) for the collection(s) you're interested in and extract to your decorations folder (either in /userdata or the root of SD2, depending on whether you have a 1 or 2 card setup), then follow the directions in the [Knulli wiki](https://knulli.org/configure/customization/bezel-decorations/). Or, you can pick and choose by navigating the various collection folders to create a custom collection. Just make sure to grab the correct info files in addition to the pngs.<br><br>
*Note that if you download the zip files, you get all of the resolutions I have available. There's no need to choose the overlays with the correct resolution as Knulli will select the most appropriate versions for your device.*<br><br>
Coverage of devices/consoles is haphazard, and each of the four collections includes different combinations of systems (availability just depends on what overlays I've made so far). I suggest configuring on a system-by-system basis using the *Per System Advanced Configuration* menu so you can use other collections for missing systems (see the [Knulli wiki](https://knulli.org/configure/customization/bezel-decorations/#system-bezel-decorations) for instructions on how to do this).<br><br>
Note that some systems have alternate versions included (denoted with hopefully self-explanatory suffixes). If you wish to use one of the alternate versions, simply delete or rename the main version and remove the suffix from the filename of your chosen version. For example, if you want to use the SP version of the 640x480 GBA overlay, you could first rename gba-640x480.png to gba-640x480_no_sp.png (or whatever) and then rename gba-640x480_sp.png to gba-640x480.png.<br><br>
Here are examples of some of my more recent overlays (some of which I haven't gotten around to uploading in my other repositories). You can find other examples in my [640x480](https://github.com/mugwomp93/muOS_Customization) and [720x720](https://github.com/mugwomp93/720x720_overlays) overlay repositories.<br><br>
***Caution: Overlays game positioning/scaling may not appear correctly if you have existing overrides saved via Retroarch. Please make sure to clear any existing overrides, or download overlays from my other repositories if you prefer to manage them via Retroarch settings instead of the Knulli frontend.***<br><br>
*Credits: All LCD grids by [1playerinsertcoin](https://www.reddit.com/user/1playerinsertcoin/submitted/). Non-integer scale 720x720 NGP and NGPC bezel designs by KugelFanger.*

### 640x480
<img width="2304" height="576" alt="640x480_examples" src="https://github.com/user-attachments/assets/ec073df9-b1b9-4d9e-ba99-2fb229ca112a" />
As mentioned above, there is also an SP version of the GBA overlay in the same style available. To use it, you just need to rename the GBA png files (the info file remains the same).

### 720x720
<img width="2380" height="1640" alt="720x720_examples" src="https://github.com/user-attachments/assets/6b6e035f-0597-4f71-bb98-0e13ad721681" />

### 1024x768
<img width="3468" height="1734" alt="1024x768_examples" src="https://github.com/user-attachments/assets/f05a6273-0d04-4458-be8d-b56ca96d662e" />
Some of these may look similar to my old versions (DMG, GBC), but I've recreated them at higher resolution so the images are crisp (unlike some of the upscaled versions floating around). Note that the game images are simulated since I don't have a 1024x768 device (others have tested these overlays, though).<br>

# [Bootlogos](https://github.com/mugwomp93/Knulli_Customization/tree/main/bootlogos)
A small selection of 640x480 and 720x720 [Knulli-themed bootlogos](https://github.com/mugwomp93/Knulli_Customization/tree/main/bootlogos). As per the [Knulli wiki](https://knulli.org/configure/customization/bootlogo/), just copy the bootlogo of your choice to the KNULLI partition of SD1 (note that as of Scarab, the batocera partition has been renamed to KNULLI, so that part of the wiki is out of date). Make sure to back up your existing bootlogo first since it will be overwritten.

### [640x480](https://github.com/mugwomp93/Knulli_Customization/tree/main/bootlogos/640x480)<br>
<img width="1536" height="576" alt="640x480_bootlogos" src="https://github.com/user-attachments/assets/1ac4544e-300e-4bc5-84d1-ffca9223aa21" />
There's also a Scarab version of the GB bootlogo available (similar to the 720x720 version shown below).

### [720x720](https://github.com/mugwomp93/Knulli_Customization/tree/main/bootlogos/720x720)<br>
<img width="1600" height="820" alt="720x720_bootlogos" src="https://github.com/user-attachments/assets/b40f29b1-cb52-47ec-9336-d140a404c1a9" /><br>
There are also a couple of other versions of the Neo Geo-style logo available (circle logo, plain black background), but this one is my favorite. The background image in the Neo Geo bootlogo is adapted from ivancristina's [vectorized version](https://github.com/ivancristina/ArcadeSketches) of angel77lopez's [arcade logos artwork](https://forums.pimoroni.com/t/new-artwork-for-picade-cabinet/2618/495). 
