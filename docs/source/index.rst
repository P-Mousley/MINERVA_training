MINERVA GIWAXS bootcamp
===============================

Below are the relevant details for preparing for the upcoming online training session for the analysis of GIWAXS data collected at the I07 beamline at diamond. The course will give general details about analysis of GIWAXS data, as well as some specific information related to the `MINERVA system`_. 

Date of next online training session:

     10 April 2026 from 09:30 to 13:00

register using this online form: `online FORM`_ 

You have time to sign up until **1/4/2026**, it won’t be possible to accept late registrations. 


Pre-session checklist:
------------------------

1. have a working fed-id and password

    if you do not already have a fed id, please follow this link to create a Diamond user account - https://uas.diamond.ac.uk  -  and then wait for instructions on how to activate your account. 

2. ability to connect to NoMachine session
    
    please follow instructions at the following link to setup the NoMachine software to connect to diamond virtual linux environment: https://www.diamond.ac.uk/Users/Experiment-at-Diamond/IT-User-Guide/Not-at-DLS/Nomachine.html 

3. ability to connect to HPC using ssh wilson

    Once you are logged into a virtual linux machine, you will need to setup your SSH connection to wilson. To do this, open a new terminal , import the fast_rsm module ussing the command
    
    .. code:: python

        module load fast_rsm
    
    and run the command. 

    .. code:: python

        ssh-instructions

    This will open a step-by-step guide to allow your SSH connection to the HPC cluster at Diamond.

 For any questions, please contact philip.mousley@diamond.ac.uk.

.. _`MINERVA system`: https://www.diamond.ac.uk/default/Instruments/Structures-and-Surfaces/I07/guide/MINERVA.html
.. _`online FORM`: https://forms.office.com/Pages/ResponsePage.aspx?id=dLonnQABDU2B_x1yja6N9mz43JA3kLVEtAFCYfypj39URDVLTE83Qk5YOFBJUEdHREZEQ05TMkFUMi4u


.. toctree::
    :maxdepth: 1

    outline
    questionset1
    questionset2
    toolbox_guide