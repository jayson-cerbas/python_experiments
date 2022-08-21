# python_experiments
Requires:
* https://www.anaconda.com/distribution
* Jupyterlab
* Numpy:
    ```commandline
    # Best practice, use an environment rather than install in the base env
    conda create -n my-env
    conda activate my-env
    # If you want to install from conda-forge
    conda config --env --add channels conda-forge
    # The actual install command
    conda install numpy
    ```
* Matplotlib:
    ```commandline
    conda install matplotlib
    ```
