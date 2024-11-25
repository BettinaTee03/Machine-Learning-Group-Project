# neurotic_networkers
ML class group project by Ewha students

Team Members:  
Qin Tong Bettina Tee  
Ryan  
Eloïne  
Jordan
Kei 

To activate the .yml file follow below
In terminal or PowerShell copy the following commands

conda env create -f mlpro.yml

conda activate mlpro

The first line will create the venv in order to have a dedicated venv that is the same across all our computers
The second line will activate the venv in order to run the program with all the required dependanceis that we are using ex pandas, numpy ect.

Be sure to activate the second command any time that you want to run the program! (its basically a python kernel)

# Brief comments on results
### Feature selection
It's interesting to see how the most important features for the multi-class models are almost the same, but are totally different from the ones for the binary classification. This could be explained by the fact that for multi-class, samples for the same website might have similar features, whereas for binary there might be no reason for two samples each from a different monitored website to be more similar than one from the monitored and one from the unmonitored or two unmonitored between themselves.

### Performance
The binary classification seems to perform much worse than the multi-class one, which could be explained by a situation of overfitting on the training data or by the fact once more that since there might not be such visualisble differences between the monitored and unmonitored websites, there are a lot of noise points. Maybe this could be improved using a model that uses clustering instead of random search.


