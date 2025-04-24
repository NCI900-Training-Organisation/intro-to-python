Getting Started
-----------------


To access the Gadi system, follow these steps:

1. **SSH into the Gadi system**:

    .. code-block:: console
        :linenos:

        ssh -XY <nci username>@gadi.nci.org.au


    Alternatively, you can use the Gadi terminal option at `ARE <https://are.nci.org.au>`_.

2. **Change to the project directory**:

    .. code-block:: console
        :linenos:

        cd /scratch/vp91
    

3. **Create and navigate to a directory with your username**:

    .. code-block:: console
        :linenos:

        mkdir -p $USER
        cd $USER
   

4. **Clone the repository**:

    .. code-block:: console
        :linenos:

        git clone https://github.com/NCI900-Training-Organisation/intro-to-python.git
        cd intro-to-python


ARE Environment
------------------


.. list-table::   
  :widths: 20 20
  :header-rows: 1   
 
  * - Fields
    - Values
  * - Walltime
    - 4
  * - Queue
    - Normal
  * - Compute Size
    - Medium
  * - Project
    - vp91
  * - Storage
    - scratch/vp91+gdata/vp91
  * - Modules
    - python3/3.11.0
  * - Python or Conda virtual environment base
    - /g/data/vp91/Training-Venvs/intro-to-python

