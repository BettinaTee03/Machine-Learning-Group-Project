# neurotic_networkers
EWHA Machine Learning 38428 class group project by team Neurotic Networkers
 
Team Members | Student ID  
-------------| -------------
Qin Tong Bettina Tee  | IES24303  
Yan Renyu | IES24364  
Eloïne Vatteville-Réveillon | IES24309  
Jordan O’Neill | IES24181  
Kei Saito | IES24601   
Roselyn Mui Huynh | IES24362 
Jennifer Zhang | IES24624


# Running the codes
## 1 Download the data
You can create a folder called 'datasets' and put the mon_standard.pkl and unmon_standard.pkl data files in it, or edit the file addresses in the code to your own folders with the data.

## 2 Create an environment

When running this project, first make sure you have `conda` installed on your machine. You can download it [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

To activate the .yml file follow below, in Terminal or PowerShell copy the following commands:

```
conda env create -f mlpro.yml

conda activate mlpro
```

The first line will create the venv in order to have a dedicated venv that is the same across all our computers.

The second line will activate the venv in order to run the program with all the required dependancies that we are using, e.g. `pandas`, `numpy` ect.

Be sure to activate the second command any time that you want to run the program! (It's essentially a Python kernel)

## 3 Create the features from the data
Run the feature_extraction.ipynb, this will create a 'extracted_features.pkl' file, containing all the features we created from the raw data.

## 4 Try the different models!
You can see our workflow and results for each experimental scenario by running the cells in the closedworld_multiclass, openworld_multiclass and openworld_binaryclass files.
Be careful of some cells that might take a long time to run depending on your machine capacities.
