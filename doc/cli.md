
KPConv-Torch is a library with a *command-line interface* (CLI). The following options are available, behind the command `kpconv`:

- `-d` or `--datapath`: path containing the dataset on the file system (mandatory);
- `-s` or `--dataset`: dataset name (default = "S3DIS");


Then, the following keywords and options are available:
- `preprocess`: corresponds to the preprocessing of the data labeled files, used for training the model
    - `-l` or `--chosenlog`: path of the KPConv log folder on the file system;
- `train`: corresponds to the training of the model;
- `test`: corresponds to the inference function of the model
    - `-f` or `--filename`: file on which to predict semantic labels starting from a trained model;
- `visualize`: visualize kernel deformations;
- `plotconv`: plot convergence for a set of models. 




