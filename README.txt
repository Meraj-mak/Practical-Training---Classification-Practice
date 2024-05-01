Installation:

 Environment Setup:
   - Ensure Python 3.x is installed.
   - Install required packages: pandas, sci kit-learn, numpy.

 Execution:

1.Load the Data:
?- Read `EdgeHistogram.csv` and `Images.csv`.
?- Merge the data on the 'ImageID' column.

2.Preprocess the Data:
?   - Split the data into features (X) and labels (y).
?   - Perform a train-test split.

3. Model Training:
?   - Train three classifiers: K-Nearest Neighbors, Naive Bayes, and Decision Tree.
?   - Perform hyper parameter tuning for K-Nearest Neighbors and Decision Tree using GridSearchCV.

4. Prediction and Evaluation
?   - Make predictions on the test set.
?   - Calculate the accuracy for each model.

5. Generate and Save Confusion Matrices:
?   - Generate confusion matrices for each classifier.
?   - Save the confusion matrices to CSV files named `group<group number>_result<result number>.csv`.

6. Save Hyper parameters:
?   - Compile the hyper parameters used for each classifier.
?   - Save the hyper parameters to CSV files named `group<group number>_parameters<result number>.csv`.

Operation:

?- Run the script in a Python environment.
?- The script will automatically perform all the steps from loading the data to saving the results and hyper parameters.
?- Output files (confusion matrices and hyper parameters) will be saved in the current working directory.

Output Files:

?- Confusion matrices: `group023_result1.csv`, `group023_result2.csv`, `group023_result3.csv`
?- Hyper parameters: `group023_parameters1.csv`, `group023_parameters2.csv`, `group023_parameters3.csv`
