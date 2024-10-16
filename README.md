FlyDisco
================

The Fly Disco is a high throughput behavioral assay designed to quantify the effects of optogentic manipulations on the behavior of groups of freely walking fruit flies including body and limb movements. Here, we provide the parts list, fabrication and assembly instructions for the Fly Disco behavioral assay. 

![image](photos/FlyDiscoRig_expansions.png)

We have included the complete specifications for our Fly Disco Hardware. Some parts are essential to replicate in order to reproduce videos that can be processed using our analysis pipeline and pretrained trackers such as the recording chamber. Other parts can be easily subsituted with little impact on video quality such as the rolling cart. We have color coded the [parts list](FlyDiscoPartsList.xlsx) with green for essential, yellow for suggested, and no color for non-essential parts, but for completeness provided all the information. 

The [3D designs](https://github.com/arobie/FlyDisco/tree/main/DesignFiles/Drawings%20and%20CAD%20Fly%20Disco%20Hardware) for the hardware were created with AutoDesk Inventor. The [assembled 3D hardware](https://github.com/arobie/FlyDisco/blob/main/DesignFiles/BRANSON%20FLY%20DISCO%20TOP%20LEVEL%20ASSY.stp) can be viewed with the free software CAD Assisant. 

   

The following are the essenital items that require custom fabriction:

0. Fly Bubble vacuum mold (3D printed or milled) - [design file](https://github.com/arobie/FlyDisco/blob/main/DesignFiles/InstructionsandDesignFiles4FlyBubbles/THERMOFORM%20BUCK%20-%20BUBBLE.pdf)
1. Bubbles (vacuum forming) - [instructions](https://github.com/arobie/FlyDisco/edit/main/README.md#:~:text=Fly%20Bubble-,Instructions,-.pdf)
2. Fly Bubble cartridge (3D printed and milled) - [design and instructions](https://github.com/arobie/FlyDisco/edit/main/README.md#:~:text=Item_Cart-,InstructionsandDeisgnFiles4FlyBubbleCartridge,-Document%20Images)
3. Base plate (milled) - [design file](https://github.com/arobie/FlyDisco/edit/main/README.md#:~:text=BLACKOUT%20PANEL.ipt-,BASE,-PLATE.ipt)
4. LED backlight and LED indicator - https://github.com/janelia-experimental-technology/RGB-IR-LED-Boards > RGB_IR Backlight 5x5



Related repositories:
<ul>
  <li>1. LED backlights https://github.com/janelia-experimental-technology/RGB-IR-LED-Boards</li>
<li>2. Data collection: FlyBowlDataCapture (FBDC) https://github.com/kristinbranson/FlyBowlDataCapture
  <ul>
   <li> Video collection: BIAS https://github.com/kristinbranson/BIASJAABA</li>
  </ul>
</li>
<li>3. Analysis Pipeline: FlyDiscoAnalysis https://github.com/kristinbranson/FlyDiscoAnalysis
    <ul>

   <li> FlyTracker https://github.com/kristinbranson/FlyTracker</li>
   <li> APT: Animal Part Tracker https://github.com/kristinbranson/APT</li>
   <li> JAABA: Janelia Automatic Animal Behavior Annotator https://github.com/kristinbranson/JAABA</li>
  </ul>
</li>
</ul>

Acknowledgements
================
Designed by Alice Robie in collaboration with the Janelia Engineering and Technology group. 
