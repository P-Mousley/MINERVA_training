MINERVA GIWAXS bootcamp
===============================

A collection of material for training I07 users on analysis of GIWAXS datasets

Date of next online training session:

     10 April 2026 from 09:30 to 13:00

Pre-session checklist:

- have a working fed-id and password

    if you do not already have a fed id, please follow this link to create a Diamond user account - https://uas.diamond.ac.uk 

- ability to connect to NoMachine session
    
    please follow instructions at the following link to setup the NoMachine software to connect to diamond virtual linux environment: https://www.diamond.ac.uk/Users/Experiment-at-Diamond/IT-User-Guide/Not-at-DLS/Nomachine.html 

- ability to connect to HPC using ssh wilson

    Once you are logged into a virtual linux machine, you will need to setup your SSH connection to wilson. To do this, open a new terminal , import the fast_rsm module and run the command ssh-instructions. This will give you a step-by-step guide to allow your SSH connection to the HPC cluster at Diamond.

    .. code:: python

        module load fast_rsm
        ssh-instructions


resources for the training session
-------------------------------------------------

- notebook for intro to data reduction
- walkthough on experiment setup file

.. toctree::
    :maxdepth: 1

    questionset1

case study notebooks
.......................

.. |colab-badge1| image:: https://colab.research.google.com/assets/colab-badge.svg
   :target: https://colab.research.google.com/github/P-Mousley/MINERVA_training/blob/testing/MINERVA_calculations.ipynb
   :alt: Open In Colab
   :height: 20px

**MINERVA Calculations set 1** |colab-badge1|



examples
- Rachael
- Emma
- Olivia


extra resources
----------------

`fast_rsm`_  readthedocs page 



.. _fast_rsm: https://fast-rsm.readthedocs.io/en/latest/diamonduse.html
.. _usage at Diamond: ./diamonduse.html