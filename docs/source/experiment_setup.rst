Creating the experiment setup file
====================================


To process your collected data you will need to create an experimental setup file, so that the fast_rsm software understands both the geometry of the setup as well as the output you would like it to calculate.



local_data_path
------------------

    Set this to the directory path where your files are saved, note you will need to include any subdirectories in this path e.g
    
    .. codeblock::python 

        /dls/i07/data/2025/si36456-5/sample1

local_output_path
---------------------

    Set this to the path where you want the output from the data processing to be saved e.g.

    .. codeblock::python 

        /dls/i07/data/2025/si36456-5/processing/sample1

setup
--------
    How was your sample mounted? Options are ‘horizontal’, ‘vertical’ and ‘DCD’



experimental_hutch
----------------------

    which experimental hutch was used 1= experimental hutch 1, 2=experimental hutch 2



beam_centre
--------------

    The beam centre, as can be read out from GDA, in pixel_x, pixel_y.

detector_distance
---------------------

    The distance between the sample and the detector (or, if using the DCD, the distance between the receiving slit and the detector). Units of meters.

process_outputs
-------------------

    define what outputs you would like from the processing in a list e.g. [‘pyfai_ivsq’]. The options available are:

        - **full_reciprocal_map**: calculates a full reciprocal space map combining all scans listed into a single volume. Use this option for scan such as crystal truncation rod scans, fractional order rod scans, or in-plane HK scans.

        - **pyfai_qmap**: calculates 2d q_parallel Vs q_perpendicular plots using pyFAI. Use this options for GIWAXS measurements either with a static detector or a moving detector.

        - **pyfai_ivsq**: calculates 1d Intensity Vs Q using pyFAI. Use this options for GIWAXS measurements either with a static detector or a moving detector.

        - **pyfai_exitangles**: calculates a 2d map of horizontal exit angle Vs vertical exit angle

map_per_image
----------------

    this option will set whether to combine all scans into a single output:

        map_per_image=False -> gives a single output file (either HKL volume or mapped GIWAXS data)

        map_per_image=True -> analyses each image individually creating multiple output files (either HKL volumes or mapped GIWAXS)

