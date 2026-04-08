Question set 2 - minimum + optional all
=========================================

Create the setup file
------------------------

Try creating your own experiment setup file using the details described below,


**experiment 1**


The experiment was conducted in experimental hutch 1 using a horizontal setup, and the data is being saved to the following path *'/dls/science/groups/das/ExampleData/i07/fast_rsm_example_data/si30563-1'*. After aligning the sample the beam centre was *(1428,978)* and the detector distance was *0.4264 meters*. You would like the mapper to calculate both Qmap and Intensity vs Q profiles, and save the output to the folder *'/home/myoutputs/'* . Additionally you would like to map each image individually, with a size of 1400 x 1400 pixels for the Qmap images, and a radialstep of 0.01 for the Intensity Vs Q profiles. You also have created a mask saved to *'/home/mymasks/mask1.edf'*. The detector positioning system was not used. 


**experiment 2**

the experiment was conducted in experimental hutch one using a horizontal geometry, and the data is being saved to the following path *'/dls/science/groups/das/ExampleData/i07/fast_rsm_example_data/si30452-2'*. The beam centre was 450 in the y-axis, and 255 in the x-axis, with the detector at a distance of 30cm. The motor thv was used to access higher incident angles. Also some of the images were corrupted and will need to be skipped - this happend for images 10,15  in scan 133675, and image 18 in scan 133676.  You would like to have all images mapped into one large qmap of q perpendicular Vs q parallel. 
