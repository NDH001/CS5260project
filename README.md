# CS5260project

There are two options to run fl_robust and FGSM.

1. Download fl_robust.ipynb,fl_defence, FGSM.ipynb and fgsm \\
   -upload these files and notebook to the google drive 
   -run the two notebook with runFromScratch = False
This is the ideal way of running the notebook since the folder already provided all the pretrained model and data needed for the executions.

2. However, if you just want to download the notebooks itself without any data, then run the notebook with the variable runFromScratch = True.
This will train the model, perform perturbated action, calculation of differential evolution etc in real time and save the end result, which is the same files we have provided in the fl_defence and fgsm. This is not recommended as it might take days or even weeks to complete differential evolution on the data and other parts that needs to train the model would slow the process too. Nonetheless, if one is interested in exploring the notebook first hand, go ahead and change runFromScratch to True.
