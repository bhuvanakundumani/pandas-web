#Installing pandas with anaconda 

1. Download [Anaconda](https://www.anaconda.com/distribution/) for your operating system and the latest Python version, run the installer, and follow the steps. Detailed instructions on how to install Anaconda can be found in the [Anaconda documentation](https://docs.anaconda.com/anaconda/install/)).

2. Create a new conda environment. A conda environment
is like a virtualenv that allows you to specify a specific version of Python and set of libraries. Run the following commands from a terminal window:

    conda create -n name_of_my_env python

This will create a minimal environment with only Python installed in it.

3. To put your self inside this environment run:

    source activate name_of_my_env

On Windows the command is:

    activate name_of_my_env

4. The final step required is to install pandas. This can be done with the following command:

    conda install pandas

To install a specific pandas version:

    conda install pandas=0.24.2

5. To import the pandas library, the command is:

    import pandas 

To import the pandas library with an alias pd, the command is:

    import pandas as pd

6. Having installed pandas, to check the version of the pandas run:

    pd.__version__

# Installing pandas from PyPI

1. To install pandas from PyPI, run the command:

    pip install pandas



