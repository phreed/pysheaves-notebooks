# pysheaves-notebooks
The samples from the class.

This is part of the [AU Sheaves Simplex Activity](http://www.american.edu/cas/darpasheaves/).

The pip install follows [this example](https://pip.pypa.io/en/latest/reference/pip_install.html#git).

Starting with an installed [Miniconda](http://conda.pydata.org/miniconda.html).
Then an appropriate environment is constructed into which pysheaf is added as a package.
The following actions should be performed from a command shell (not a PowerShell as conda is not compatible).

    conda create -n sheaves jupyter numpy scipy matplotlib networkx
    activate sheaves
    pip install -e git+https://github.com/phreed/pysheaf.git@master#egg=pysheaf

Clone this repository to some convenient folder.
Change to the new folder and start the jupyter notebook.

    jupyter notebook
    
This will start the notebook server and open your browser
with the initial page being the index of the notebook.

For more information on [using Jupyter](https://jupyter.readthedocs.org/en/latest/).
