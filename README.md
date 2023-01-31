# Welcome to GRDF: a novel method for identifying anticancer peptides with deep graphical representation based on deep forest


**Welcome to GRDF, a deep forest-based ACP prediction tool developed by a team from the Chinese University of Hong Kong (Shenzhen)**

GRDF integrates graphical information based on FEGS, evolutionary information and binary profile information.

We provided our datasets (Set 1 and Set 2) and you can find them [here](https://github.com/Martinyao1998/GRDF/tree/main/dataset "here").

First you need to install the Python environment for Deep Forest, via the following command.

    pip install deep-forest

For details of this python package, please refer to the API [here](https://deep-forest.readthedocs.io/en/latest/ "here").

- For information on how to obtain FEGS features please refer to [FEGS](https://github.com/Martinyao1998/GRDF/blob/main/Code%20for%20extracting%20features/FEGS.rar)
- For the code to obtain evolutionary information please refer to [BLOSUM62.ipynb](https://github.com/Martinyao1998/GRDF/blob/main/Code%20for%20extracting%20features/BLOSUM62.ipynb)
- For the code to obtain binary profile please refer to: [Binary Feature.ipynb](https://github.com/Martinyao1998/GRDF/blob/main/Code%20for%20extracting%20features/Binary%20Feature.ipynb)
After extracting these features, you can use them to build a deep forest-based model to predict the ACP. You can refer to the following notebooks.

1. [Dataset Statistics.ipynb](https://github.com/Martinyao1998/GRDF/blob/main/Dataset%20Statistics.ipynb "Dataset Statistics.ipynb") is a code example allows you to plot the length distribution of peptide sequences and their mean amino acids composition (Mean AAC).

2. [Constructing model to predict ACP.ipynb](https://github.com/Martinyao1998/GRDF/blob/main/Constructing%20model%20to%20predict%20ACP.ipynb "Constructing model to predict ACP.ipynb") is a quick tutorial that tells you how to build an ACP prediction model using Deep Forest and perform cross-validation.

3. [Use trained model.ipynb](https://github.com/Martinyao1998/GRDF/blob/main/Use%20trained%20model.ipynb "Use trained model.ipynb")  is a quick tutorial that shows you how to use an already established deep forest model.


If you have any questions, please feel free to contact me.

**Name: Lantian Yao
Email: lantianyao@link.cuhk.edu.cn**


