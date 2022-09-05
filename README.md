# FakeNewsClassifier
Given as set of data containing news articles, let's classify which is fake vs real news.

### Software, Tools, and prerequisits
1. Access to Google Colab or some Jupyter Notebook.
2. Basic python programing.
3. Basic ML knowledge

### Steps to completing the project
1. Import the necessary modules/ pachkages (eg. pandas, numpy, sklearn, etc).
2. Read the provided datasets ($True.csv$ and $Fake.csv$).
3. Seperate the last 10 items from each dataset for validation.
4. Combine both seperated sets from $Step3$ into 1 file.
5. Perform some basic plotting/ visualization of the main datasets ($True.csv$ and $Fake.csv$). 
6. Drop empty/$NA$ columns.
7. Using regular expressions, filter unwanted characters and convert all text to lowercase.
8. As this is a Superviced Learning approach, split the data into training and test sets.
9. Vectorize the inputs of the dataset.
10. Use each of the recomended classifiers ($Logistic Regression, Decision Tree, Gradient Boost, Random Forest$)
11. Test the model...
