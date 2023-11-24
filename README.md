**Linear Regression Models with Feature Encoding**

This repository contains Python code for implementing linear regression models on a dataset using different feature encoding techniques.

**Label Encoding:**
In the label_encoding.ipynb notebook, the data is loaded from a CSV file, and label encoding is applied to specific columns using a custom transformer (LabelEncoderTransformer). The label-encoded features, along with one-hot encoding for selected columns, are part of the preprocessing pipeline. The linear regression model is then trained, and its performance is evaluated using mean squared error.

**Usage:**

**1. Install Dependencies:**

Make sure you have the required libraries installed by running pip install -r requirements.txt.

**2. Run the Jupyter Notebook:**

Open and run the label_encoding.ipynb notebook to see the implementation.

**3. Adjust File Paths:**

Replace the file path in the code with the actual path to your CSV file.

**4. Explore and Experiment:**

Feel free to explore the notebook, modify the code, and experiment with different parameters.


**One-Hot Encoding:**
In the one_hot_encoding.ipynb notebook, the data is loaded from a CSV file, and one-hot encoding is applied to selected columns using the OneHotEncoder. The one-hot encoded features, along with standard scaling, are part of the preprocessing pipeline. The linear regression model is trained, and its performance is evaluated using mean squared error.

**Usage:**

**1. Install Dependencies:**

Make sure you have the required libraries installed by running pip install -r requirements.txt.

**2. Run the Jupyter Notebook:**

Open and run the one_hot_encoding.ipynb notebook to see the implementation.

**3. Adjust File Paths:**

Replace the file path in the code with the actual path to your CSV file.

**4. Explore and Experiment:**

Feel free to explore the notebook, modify the code, and experiment with different parameters.


**Dataset:**
The code assumes a dataset in CSV format with features and a target variable ('default'). Ensure that your dataset follows a similar structure for seamless execution.
