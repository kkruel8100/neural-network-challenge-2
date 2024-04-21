### Welcome to Kim's Neural Network Challenge #2

where we use Standard Scaler, TensorFlow, and Sklearn for deep learning with neural networks.

#### Overview

Showcasing Python, Pandas, Sklearn, and Tensor Flow, the challenge gathers information about employees. It is used to predict whether employees are likely to leave and the department that would be the best fit for an employee. It creates a y_df for the attrition and department columns. It then creates a X_df using 10 different columns from the original data and separates them in train and test and scales the data.

The columns' datatypes are reviewed, and the column with object dtype and only 2 values is transformed using label encoder. The label encoder is fitted on the train data, and both train and test are transformed.

A standard scaler is created and fitted on the train data, and both train and test are transformed.

One hot encoder is created for both the attrition and department columns. It is fitted on the y_train data and transforms both the y_train and the y_test.

A branched neural network is created. It contains input layer, two shared layers, a department hidden and output layer, and an attrition hidden and output layer. The model is compiled and then summarized. The model is fitted with the X_train_scaled, department_train_encoded, and the attrition_train_encoded. The model is then evaluated using the corresponding test data. The accuracy results are printed.

Summary Q&A reviews the output from an analytical viewpoint and identifies potential areas for improvement.

#### Program

    └───root
        │   README.md
        └───attrition.ipynb

Step 1:

Navigate to the "attrition.ipynb" file in GitHub repo. The output for each panel can be viewed in the "Preview" panel.

Alternatively,

Step 1:

Clone the repository.

Step 2:

Go to Google Colab

Step 3:

File upload

Step 4:

Select "attrition.ipynb".

Step 5:

Under "Runtime", select "Run All".

Step 6:

Review output panels.

#### Resources

The data was supplied as starter code by ASU edX Boot Camps, LLC.

The data is located at [https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv](https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv)
