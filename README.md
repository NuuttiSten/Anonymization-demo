
    $ conda create --name anonymization-demo

Proceed

    $ conda activate anonymization-demo
    $ conda install pip

Proceed

    $ git clone https://github.com/Datahel/tabular-anonymizer.git
    $ pip install pip install -e tabular-anonymizer

    $ conda install notebook ipykernel
    $ ipython kernel install --user --name anonymization-demo --display-name "Python (anonymization-demo)"

Choose the new kernel Python (anonymization-demo) from the list in the notebook interface.

Finally

    $ conda deactivate


The following does not work at the moment

    $ pip install https://github.com/Datahel/tabular-anonymizer.git