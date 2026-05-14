# Credit-Risk-Prediction-
Credit Approval Prediction Using Support Vector Machines (SVM) and Multilayer Perceptron’s (MLP)


**Software Requirements:**
- Python 3.8 or higher
- Jupyter Notebook
- Required libraries (install with pip if needed):
    pandas
    numpy
    scikit-learn
    imbalanced-learn
    matplotlib
    seaborn
    joblib
    lime

**To reproduce the experiments and figures:**
1. Open `Neural_Network_FINAL_CODE.ipynb` in Jupyter Notebook.
2. Run all cells sequentially to preprocess the data, train SVM and MLP models, and generate the main figures (such as confusion matrices, learning curves, ROC curves).
3. The notebook is fully commented for clarity.

**To test the saved models:**
1. Open `NN_Test_File.ipynb`.
2. Ensure the `Testing/` folder with `best_mlp_model.pkl`, `best_svm_model.pkl`, and `test_data.csv` is in the same directory.
3. Run the notebook to load the models and make predictions on the test data.




**If you need the original dataset:**
- The anonymized UCI Credit Approval dataset can be downloaded from:  
  https://archive.ics.uci.edu/dataset/27/credit+approval

-------------------------------------------------
NOTES ON CODE REPRODUCIBILITY & REFERENCES
-------------------------------------------------

- All code is original unless otherwise stated in comments. Any external code or AI-generated code is clearly referenced in the notebook comments.
- Software/library versions used for development:
    - pandas 1.5+
    - numpy 1.21+
    - scikit-learn 1.0+
    - imbalanced-learn 0.9+
    - matplotlib 3.5+
    - seaborn 0.12+
    - joblib 1.1+
    - lime 0.2+
- If you encounter version issues, please use the versions above for best compatibility.

