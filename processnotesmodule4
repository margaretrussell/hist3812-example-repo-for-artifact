### Introduction:
  
  For this module, we attempted to create an augmented reality display of our 3D model from the first module. However, we decided to provide
  a different perspective on it by allowing the viewer of the model in its augmented reality version to switch between it and a modified 
  version of the model. In this way, the viewer could see the hippo statue in augmented reality both with and without the legs broken off 
  (as it was originally found with three legs broken during the excavation). To operate the display, the viewer would use the HP Reveal 
  app to scan a designated “trigger image”, wait for the 3D model to appear on screen, and then tap the model to toggle between views. We 
  believe this display has interesting potential as it allows a viewer to see two different modes of an object’s “being” without having to 
  damage the object itself or alter it beyond the possibility of returning to its original state. Kurt worked mainly on creating the “Aura”
  for the augmented reality display through HP Reveal and on the paradata, while Margaret gathered historical information on the statue’s 
  changing state over time and also helped work on some of the paradata.

### Process Notes:

-March 30th: Kurt signed up for an HP Reveal account. He began working on an “Aura” project and uploaded an image of the original William 
statue as the “trigger image” (downloaded from google images). He then tried to overlay the image with the original 3D model of William in 
the .tar format - this was created by exporting the model from Meshmixer in a .dae format and archiving it with 7zip. Unfortunately, HP 
Reveal would not accept the model because it claimed it was “unable to locate the thumbnail”. Kurt, not knowing where the thumbnail was 
stored for the model, decided to email the professor for assistance.

-March 31st: Kurt received an email from the professor with a suggested solution. He found that he needed to add an image file named 
“thumbnail.png” to the .tar file, so he downloaded one. He tried attaching this to the .tar file, but a new error appeared when he tried to
upload the .tar file to HP Reveal, claiming that it was “missing library_materials”. Kurt emailed the professor once again.

-April 1st: Kurt received a response from the professor with more suggestions. He examined some of the troubleshooting options for 3D 
models in HP Reveal. He found that he had not chosen a thumbnail image of appropriate size, and so used Gimp to re-size the image to 
256x256 dimensions. However, attaching this to the .tar file and uploading it to HP Reveal resulted in the same “library_materials” error as
before. Kurt downloaded the example model from HP Reveal to examine whether there were any differences in it that might help him solve the 
issue as to why the .tar file was not accepted. Kurt tried uploading the example “Aurasmabox” .tar file as an overlay for his trigger image
to test whether this would work - it was successful. Kurt noticed that within this .tar file, the .dae file and its corresponding .png file
were given the same name; he also noticed that he had been using a .jpg file instead of a .png file (for the image that was not the 
“thumbnail”) in his .tar file, so he tried converting this .jpg and constructing a new .tar file that included .dae and .png files of the 
same names. Unfortunately, uploading this .tar file only resulted in the same “library_materials” error.

-April 2nd: Kurt once again sought the advice of the professor. After a period of trying a number of different solutions, the professor foun
d that it was only by saving the textures as a .png file and editing the .dae file in Sublimetext so those specific textures were linked to
the model that HP Reveal would accept the model for uploading. The model also had to be drastically reduced in quality using tools in 
Meshlab before it would fall within the acceptable file size range for HP Reveal. The model, however, when tested with the app, appeared 
too small to see. This turned out to be an issue with the scale of the original model; the model was edited in Meshlab to increase its size,
then re-uploaded via the .tar file. Unfortunately, testing this configuration revealed that the model was upside-down and entirely black - 
it had lost all of its textures for unknown reasons.

-April 5th: Kurt managed to edit the model in HP Reveal so that it would appear right-side-up in its positioning from the preview on the 
computer screen. Unfortunately, when he tried testing this new view with the phone app, the image was recognized but the model never loaded
, simply displaying the continuous “loading” animation instead.

-April 6th: Kurt moved the relational position of the model in the HP Reveal display and changed the picture to test it once more. At this 
point, the model began to load. He then opened a copied version of the .dae model file in Meshlab and edited out much of the background, as
well as cutting out William’s legs for an “alternate display” of the model. Margaret found which legs were the ones found broken during the
excavation in order to ensure the greatest accuracy possible in this step. He uploaded this as a second overlay in HP Reveal as a .tar file
, combined once again with the texture and thumbnail images. He repositioned this second model, then set the second (with the broken legs) 
to remain hidden when the “Aura” was activated. He added to each overlay so that if each was tapped, it would stop and the other overlay 
would start, allowing the viewer to switch between the models. Finally, he changed the image to a background of pyramids with a sentence 
imposed over it (added by editing the image in Gimp) instructing the viewer on how to switch views. Unfortunately, neither model’s textures
loaded properly and both remained entirely black, making it difficult to see the spaces where William’s legs were removed.
