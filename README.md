# NUC10ExpansionCase
A 3d printed chassis extension for Intel NUC 10ixfnk (the shorter variant).
idk about 11+ gen, Intel is not super helpful when it come to documenting their internal sATA connectors but
it should be easily modifiable to fit as long as the outer case dimensions are the same.
You will need a couple of things to complete this project, the print takes about 5 hours so this can reasonably be completed in a day.
The hardware is easy enough to acquire but the proprietary-ish internal sATA connector that Intel uses is somewhat hard to find.

PARTS LIST:
1. 4x's 20mm M3 standoffs
2. 4x's m3 threaded inserts for VESA and sATA mounts
3. Intel NUC Internal FPC/FCC 22 Pin SATA/Power Cable for 2.5 Inch Drives, delicate so buy a spare just in case, found here (for now...): https://www.amazon.com/Intel-Internal-SATA-Power-Drives/dp/B0931VSHX4/ref=sr_1_1?keywords=Intel+NUC+Internal+FPC%2FFCC+22+Pin+SATA%2FPower+Cable+for+2.5+Inch+Drives&qid=1639009036&sr=8-1
  - Alternatively you can modify the file and add a slot to back of the case and pass a usb3.0 to sata3 cable though it
4. The feet/screws and e-clips from the original baseplate
5. 4x's rubber o-rings for hdd dampening <= ~3mm ID
6. 4x's m3 flat head head screws (length depends on dampers used, try 10-15mm to start or just get a bundle of assorted lengths)
7. 2x's m3 rounded head screws (again depends on dampers used, that assorted screw bundle is looking pretty good right about now ;)

INSTRUCTIONS:
Turn off the computer safely and disconnect peripherals and power. 
Unscrew the metal baseplate and remove the 4 captured feet, don't loose the e-clips (when removing e-clips throw a rag over them so they don't eject into the aether). 
Screw the standoffs into the chassis, a little more than hand tight. 
The feet/screws are captured by the e-clips, mount them in the corner holes. 
Heat the threaded inserts and insert into the VESA and sATA hole patterns. 
Insert the flat head screws into the hard drive mounting holes and slide the o-rings down onto them. 
Insert the sATA connector into the hard drive (careful, the ribbon cable likes to break off at the connector, and is realistically unfixable). 
For added security hot glue the base of the ribbon cable to the sATA connector. 
Mount the hard drive to the case by gently tightening until the o-rings are squished a little (make sure the screws aren't bottoming out in the hard drive). 
Open the internal header on the motherboard by pulling the white horseshoe tab straight out (this is also very delicate). 
CAREFULLY route the ribbon cable so that is has minimal bends and twists when it's mounted in the correct orientation (the case is symmetric so just pick whatever orientation stresses the ribbon cable the least). 
Insert the ribbon cable contacts into the motherboard connector and push the tab down to lock it in place. 
Mount the 3d printed chassis to the NUC by hand tightening the feet/screws (if over tightened then the standoffs will come out too). 
Et voila! When you boot into the OS just check for the new drive and format it. 
