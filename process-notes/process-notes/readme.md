# readme

### Introduction:

For the first step of our project, we will attempt to make a digital 3D model from a reproduction of “William” the faience hippopotamus from the Metropolitan Museum of Art. Initially we placed one spotlight on William, but finding it too dark to get accurate pictures, we elected to add another to counteract any shadowing that could affect Scann3D’s or Regard3D’s ability to make a model. We decided to make our first model with Regard3D because it takes the longest to process; thus while it processes, we continue to take pictures using Scann3D. To keep human error to a minimum, or at least account for differences in each member's photography style, we decided to have one person (Kurt) do one set, and, if neither Scann3D nor Regard3D results are satisfactory, we will have the other person (Margaret) do another set. We will take the best of the first set if they are both satisfactory. As a final note, it may be worth mentioning that neither of us have experience with photogrammetry or 3D modelling and we have only very minimal experience with programming-level computer skills.

### Process:

-Jan. 22nd: on first attempt to create a model, 32 pictures of William from Kurt’s phone camera were uploaded to Regard3D. Unfortunately, due to Regard3D’s inability to read the camera’s focal length, the program failed to produce a model under its standard settings. More work may be attempted on this at a later point.

-The second attempt by Kurt took over 80 pictures of William for a low-quality model on Scann3D. This model seemed to be a fairly accurate representation of William, except for the mouth of the hippopotamus, which was apparently obscured in most pictures and appeared as a vague, jagged surface in the model.

-A third attempt was made by Margaret using Scann3D, this time with 47 pictures of William. Margaret took more pictures of the hippo’s face to see if this would make a difference in the model. Unfortunately, though the face was smoother in the final model, its texture remained inconsistent.

-Jan. 29th: another attempt was made by Kurt using Regard3D. This time, the pictures were updated with the proper metadata using exiftool in hopes of the program recognizing it. Unfortunately, the program did not on its first attempt. One more attempt was made, this time selecting the option “Global Structure From Motion” instead of “Incremental Structure From Motion” in the Triangulation stage. This seemed to make a difference, in that it did result in a model - but the model was not very coherent, even after generating a dense point cloud. Only a portion of the object scanned was truly visible in it and it did not compare to the Scann3D models in quality.

-Feb. 1st: one final attempt was made by Kurt to create a model using Regard3D. This time, only 16 of the original 32 pictures of William were used. A model was created using the “Incremental Structure From Motion” option in the Triangulation stage. However, while this model was the most coherent from Regard3D yet, it was still missing chunks of the figure and was not as satisfactory as the Scann3D models. It was decided that a Scann3D model would be used instead.

-Feb. 3rd: the trial version of Scann3D was activated, but there was a slight complication in that the location of the exported file was unclear - thus the files could not be found. Fortunately, a workaround was found through sharing the model to Sketchfab and downloading the files from there. The initial upload of the model has now been completed.
