# ollivanderslamp
## Magic lamp based on Sean O'Brian, revised by mamacker
Updates base on Python 3 

## Hardware:

### The IR array / pi camera assembly

Files included:

   IR array and controller - photo of the IR array and the PC board which interfaces
		to the 12V power.  
   IR array front - photo showing the IR array.  
   IR array full set - photo of the IR array, controller, and 12V power block.  
   IR Camera Adaptor Plate.skp - SketchUp file of the adaptor plate used to attach
		the camera to the back of the IR array.  
   IR Camera Adaptor Plate.pdf - top view of the adaptor plate and the IR array.  
   IR Camera Assembly Photo.jpg - picture of the completed assembly
	
The IR camera array attaches the camera behind the IR array, so that the field of view
for the camera, through the center hole of the IR array, is fully illuminated by The
four IR LEDs of the array.  The diffusers are not used as they get into the field of
view.

The three existing holes around the array are enlarged with a #41 drill to accomodate
a 2-56 x 1.25 mm bolt.  Three bolts hold the adaptor plate to the IR array.  4 mm spacers
separate the adaptor plate from the IR array.  Four 2-56 x .6 mm bolts hold the pi
camera to the adaptor plate.

## Software:

### trained.py is based on the mamacker/pi_to_potter trainedwpins.py

Changes made:

   updated to Python 3  
   added () to print statements  
   added background subtraction  
   added io for lights, etc, renaming pins  
   changed selection of spells  
   updated command line arguments:  
      --trace   print trace and additional lines to help diagnose problems  
      --bgsub   subtract background to enhance signal definition  
   added in the code for background subtraction and trace printing
