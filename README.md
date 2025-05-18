# Decision-tree-Implementation
Company: CODTECH IT SOLUTIONS

Name: HARINI N

Intern ID:CT04DL783

Domain: MACHINE LEARNING

Duration:4 weeks

Mentor : NEELA SANTHOSH

DESCRIPTION:

A Decision Tree is one of the simplest and most powerful tools in machine learning. Let me tell you how i developed decision tree:
 Step 1: Load the Dataset
The first step is to load your data. We usually use a CSV (comma-separated values) file for this. In Python, the library Pandas is used to load and manage datasets. You use pd.read_csv("filename.csv") to load the file in google colab. 

Step 2: Identify Features and Target:
Features: These are the columns that help us make a prediction. Think of them as input.
Target: This is what you are trying to predict. Think of it as the output.
to predict whether DSLR cameras are allowed at a tourist place, your features might include:
Zone,
State,
Time needed to visit,
Review rating,
Entry fee,
Significance, etc.
And your target would be: DSLR Allowed.

Step 3: Handle Categorical (Text) Data
Machine learning models like Decision Trees work with numbers, not words. So, you need to convert this text into numbers.

This is done using Label Encoding, which replaces words with numeric codes. For example:

"Yes" → 1

"No" → 0

"Temple" → 0, "Museum" → 1, etc.

In Python, we use the LabelEncoder class from scikit-learn for this. You need to loop through each column and convert any column that has text into numbers.

Step 4: Train the Decision Tree
Now that your data is numeric, you can build the decision tree. You split the data into a training set (for learning) and a test set (for checking accuracy). Then, you train the tree using the fit() function.

Step 5: Evaluate the Model
After training the tree, you test it using the predict() function and measure how accurate it is using accuracy_score. This tells you how good your model is at making correct predictions.

Step 6: Visualize the Tree
One great thing about Decision Trees is that they can be visualized. You can see how the model makes decisions at each level. We use tree.plot_tree() from scikit-learn.
and by these steps involuving in the program a decision tree is visualized.
