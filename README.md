# Retractometrics

Retractometrics is a Python package designed to process and compute research metrics based on retraction data. It provides various utilities for handling datasets, calculating key research metrics, and performing retraction analysis. The package aims to help researchers, data scientists, and organizations track research integrity, analyze trends, and identify instances of scientific misconduct.

## Installation

Mandatory Instructions:

1. In order for to extract a tangible output for analysis, make sure to store all the data (.csv) files in a folder with any name of your choice. It is mandatory for your data folder to be in the same directory where your code is present.

2. Install from a local directory: Navigate to the directory containing your retractometrics package and run:

    pip install .  

3. Install from a remote package (e.g., PyPI): you can install it using:

    pip install retractometrics

4. Then do :
    a. retractometrics.run()
    b. Pass the data directory path as input
    c. All the csv files will be processed and metrics will be computed
    d. Navigate to the same data folder and check for another folder named "Output_main" which contains all the metrics.

5. If you would like to compute individual metrics, you will have to extract the particular features yourselves using pandas. Unfortunately the package does not have such flexibility as of now.

6. The package is built specifically for Scopus research data, which caters well to retracted papers. However, if you choose to download data from different sources, do make sure to structure the data as per Scopus norms.

