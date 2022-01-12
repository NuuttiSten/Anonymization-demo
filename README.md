
    $ git clone git@github.com:Datahel/Anonymization-demo.git
    $ cd Anonymization-demo
    $ conda create --name anonymization-demo

Proceed

    $ conda activate anonymization-demo
    $ conda install pip

Proceed

    $ git clone git@github.com:Datahel/tabular-anonymizer.git
    $ pip install -e tabular-anonymizer
    or
    try $pip install https://github.com/Datahel/tabular-anonymizer.git
    when tabular-anonymizer is public repo
    
    $ conda install notebook ipykernel
    $ ipython kernel install --user --name anonymization-demo --display-name "Python (anonymization-demo)"

Choose the new kernel Python (anonymization-demo) from the list in the notebook interface.

    Run notebook tabular-tabular-anonymizer-demo.ipynb

Finally

    $ conda deactivate
