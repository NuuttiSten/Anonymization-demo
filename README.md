
 This is a demo for using Helsinki Tabular anonymizer.
 
 To install this demo:
 
    $ git clone git@github.com:Datahel/Anonymization-demo.git
    $ cd Anonymization-demo
    $ conda create --name anonymization-demo # or use virtual environment of your choise
    $ conda activate anonymization-demo
    $ conda install pip
    $ git clone git@github.com:Datahel/tabular-anonymizer.git
    $ pip install -e tabular-anonymizer
    or try 
    
    $pip install https://github.com/Datahel/tabular-anonymizer.git
    when tabular-anonymizer is public repo
    
    $ conda install notebook ipykernel
    $ ipython kernel install --user --name anonymization-demo --display-name "Python (anonymization-demo)"

Run notebook tabular-tabular-anonymizer-demo.ipynb
Choose the new kernel Python (anonymization-demo) from the list in the notebook interface.

Finally when you stop working:

    $ conda deactivate
