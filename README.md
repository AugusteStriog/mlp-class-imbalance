# Class Imbalance in Deep Neural Networks

This project explores strategies for addressing class imbalance in deep neural networks.

## Prerequisites: 
Ensure you have Python installed on your computer.

## Instructions:
Download the script and the dataset:
```git clone https://github.com/AugusteStriog/mlp-class-imbalance.git```

Go to the cloned repository.

## How to Run on VS Code
The recommended way to run this project is using **[Visual Studio Code (VS Code)](https://code.visualstudio.com/)**.
1. **Open the project folder in Visual Studio Code (VS Code)**.
2. Open any `.ipynb` notebook file.
3. Click **Run All** to execute all cells in the notebook.
4. When prompted to select a kernel:
   - Choose **Python Environments**.
   - Select **Create Python Environment**.
   - Pick **Venv**.
   - Select a Python version (e.g., `Python 3.13.1 64-bit`).
5. Open the **terminal** inside VS Code and run the following command to install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn notebook

## File Descriptions
In the repository there are four folders, each has scripts used for different data sets.

### Irisai/  
- **iris** Confusion matrix using the full Iris dataset
- **iris_reduced_minority_dataset_30** Confusion matrix after removing 20 Versicolor samples
- **iris_reduced_minority_dataset_20** Confusion matrix after removing 30 Versicolor samples
- **iris_reduced_minority_dataset_10** Confusion matrix after removing 40 Versicolor samples
- **iris_reduced_minority_dataset_5** Confusion matrix after removing 45 Versicolor samples
### Širdies ligos/
- **iheart_disease_original** Results using various imbalance handling methods on the original dataset
- **heart-confusion-matrix**  Results on a version of the dataset with reduced minority class to highlight method effects
- **heart_confusion_matrix_cross** Same as above, but with cross-validation
- **heart_removed_columns**  Shows how removing features affects results with different methods
- **heart-layers-epoch**    Comparison of different MLP layer depths on the imbalanced dataset
### Insultas/
- **stroke-analysis-confusion-matrix**   Effects of sampling methods on an imbalanced stroke dataset
- **stroke-analysis-confusion-matrix-cross**  Same as above, with cross-validation
- **stroke-layers-epoch.py**  Comparison of MLP architectures on stroke data

- **stroke-analysis-smote-removed-column**  Impact of feature removal with different sampling methods
### Diabetas/
- **diabetes-analysis-confusion-matrix**   Effects of sampling methods on an imbalanced diabetes dataset.
- **diabetes-analysis-confusion-matrix-cross**   Same as above, with cross-validation
- **diabetes-analysis-removed-column**  Effect of removing features using different methods
- **diabetes-analysis-layers-epochs** Comparison of different MLP architectures on diabetes data
> All diabetes scripts use a large dataset and they take a long time to run.
## Important note!
When using Jupyter Notebooks, run the cells in order or use "Run All" to avoid errors.


