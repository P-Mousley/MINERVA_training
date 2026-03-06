Question set 1
==============================

Create the setup file
------------------------

Try creating your own experiment setup file using the details described below, then compare to the example setup file by clicking the expandable text underneath. 

**experiment1**

The experiment was conducted in experimental hutch 1 using a vertical setup, and the data is being saved to the following path *'/dls/science/groups/das/ExampleData/i07/fast_rsm_example_data/si30563'*. After aligning the sample the beam centre was *(1428,978)* and the detector distance was *0.4264 meters*. You would like the mapper to calculate both Qmap and Intensity vs Q profiles, and save the output to the folder *'/home/myoutputs/'* . Additionally you would like to map each image individually, with a size of 1200 x 1200 pixels for the Qmap images, and a radialstep of 0.01 for the Intensity Vs Q profiles. You also have created a mask saved to *'/home/mymasks/mask1.edf'*. The detector positioning system was not used. 


.. collapse:: ANSWER - click to view full example setup file

    .. code-block:: python

        setup = 'vertical'
        experimental_hutch=1
        local_data_path =   '/dls/science/groups/das/ExampleData/i07/fast_rsm_example_data/si30563'
        local_output_path = '/home/myoutputs/'
        beam_centre = (1428,978)
        detector_distance =0.4264
        qmapbins=(1200,1200)
        radialstepval=0.01
        edfmaskfile= '/home/mymasks/mask1.edf'
        process_outputs=['pyfai_ivsq']
        map_per_image = True


run the processing
---------------------