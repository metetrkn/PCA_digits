# Principal Component Analysis - Handwritten Digits

    This repository contains a Python script that demonstrates Principal Component Analysis (PCA) on a dataset of handwritten digits. The goal is to determine which handwritten digits are the hardest to tell apart using PCA.

## Dependencies

        Python 3.6 or later
        numpy
        pandas
        matplotlib
        seaborn
        scikit-learn

    You can install the required dependencies using the following command:

    bash

    pip install numpy pandas matplotlib seaborn scikit-learn

## How to use

    Clone the repository.
    Run the script pca_handwritten_digits.py in your Python environment.

## The script will:

    Load the dataset and display the first few rows.
    Create a new DataFrame called pixels that consists only of the pixel feature values by dropping the number_label column.
    Display an example image from the dataset.
    Scale the pixel feature DataFrame using Scikit-Learn's StandardScaler.
    Perform PCA on the scaled pixel data set with 2 components and calculate the explained variance.
    Create a scatterplot of the digits in the 2-dimensional PCA space, color/label based on the original number_label column in the dataset.
    Identify the most distinct numbers based on the scatterplot.
    Perform PCA with 3 principal components (bonus challenge).
    Create an interactive 3D plot of the results from PCA with 3 principal components (bonus challenge).

## Results

    The scatterplot of the digits in the 2-dimensional PCA space shows that digit 4 is the most distinct and separated from the other digits. Digits 2, 6, and 9 are also relatively distinct. The 3D plot provides a more detailed view of the separability between the handwritten digits.

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
