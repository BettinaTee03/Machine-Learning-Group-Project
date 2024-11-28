# neurotic_networkers
ML class group project by Ewha students

Team Members:
Qin Tong Bettina Tee
Ryan
Eloïne
Jordan
Kei
Roselyn

When running this project, first make sure you have `conda` installed on your machine. You can download it [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

To activate the .yml file follow below, in Terminal or PowerShell copy the following commands:

```
conda env create -f mlpro.yml

conda activate mlpro
```

The first line will create the venv in order to have a dedicated venv that is the same across all our computers.

The second line will activate the venv in order to run the program with all the required dependancies that we are using, e.g. `pandas`, `numpy` ect.

Be sure to activate the second command any time that you want to run the program! (It's essentially a Python kernel)

# Brief comments on results
### Feature selection
It's interesting to see how the most important features for the multi-class models are almost the same, but are totally different from the ones for the binary classification. This could be explained by the fact that for multi-class, samples for the same website might have similar features, whereas for binary there might be no reason for two samples each from a different monitored website to be more similar than one from the monitored and one from the unmonitored or two unmonitored between themselves.

### Performance
The binary classification seems to perform much worse than the multi-class one, which could be explained by a situation of overfitting on the training data or by the fact once more that since there might not be such visualisble differences between the monitored and unmonitored websites, there are a lot of noise points. Maybe this could be improved using a model that uses clustering instead of random search.
