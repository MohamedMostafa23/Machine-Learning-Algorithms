# Human Activity Recognition from Wearable Sensors

A team coursework project using a four-activity subset of the PAMAP2 Physical Activity Monitoring Dataset. The question was whether a reduced set of measurements could still distinguish activities. The dataset includes inertial measurements and heart-rate recordings; this exercise used data from eight participants for the selected activities.

## What the project shows

- [Data preparation](Data_Processing.ipynb): load the protocol files, select activities and features, and save processed tables.
- [Model selection](Gridsearch_ground.ipynb): explore hyperparameters for classical classifiers.
- [Model comparison](Modeling%26results.ipynb): compare logistic regression, nearest neighbors, random forest, decision tree, and SVM under different preprocessing choices.
- [Project report](Human_activity_recognition.pdf): see the full project discussion and results.

The original comparison found that logistic regression remained competitive on the selected subset. The reported scores describe this course experiment; they should not be read as performance on unseen participants without a documented participant-level evaluation.

## Reading the notebook

The original workflow expects PAMAP2 protocol files and local CSVs produced by the preprocessing notebook. To browse the work on GitHub, open the model comparison notebook and skip to the saved classification reports and figures.
