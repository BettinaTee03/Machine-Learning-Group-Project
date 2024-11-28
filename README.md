# neurotic_networkers
ML class group project by Ewha students

Team Members:  
Qin Tong Bettina Tee  
Ryan  
Eloïne Vatteville-Réveillon  
Jordan
Kei 



### Running the codes
## 1 Download the data
You can create a folder called 'datasets' and put the mon_standard.pkl and unmon_standard.pkl data files in it, or edit the file addresses in the code to your own folders with the data.

## 2 Create an environment

To activate the .yml file follow below
In terminal or PowerShell copy the following commands

conda env create -f mlpro.yml

conda activate mlpro

The first line will create the venv in order to have a dedicated venv that is the same across all our computers
The second line will activate the venv in order to run the program with all the required dependanceis that we are using ex pandas, numpy ect.

Be sure to activate the second command any time that you want to run the program! (its basically a python kernel)

## 3 Create the features from the data
Run the feature_extraction.ipynb, this will create a 'extracted_features.pkl' file, containing all the features we created from the raw data.

## 4 Try the different models!
You can see our workflow and results for each experimental scenario by running the cells in the .. .. .. files.
Be careful of some cells that might take a long time to run depending on your machine capacities.
