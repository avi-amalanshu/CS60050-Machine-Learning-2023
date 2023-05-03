# Heart Disease Prediction using Support Vector Machines (HDSVM)
## Avi Amalanshu (20EC30063), Anamitra Mukhopadhyay (20CS30064), Chavle Abhishek Shivanand (22CS60R79)
This repository contains code for the project "Heart Disease Prediction using Support Vector Machines (HDSVM)". This is a part of the Machine Learning (CS60050) course offered at IIT Kharagpur in the Spring semester 2023.  The objective is to compare the performance between various kernel functions for SVM classification on a biological dataset. The file ```ProblemStatement.pdf``` contains the precise problem statement for this project.
### If you are running the experiment on Google Colab
 You must ensure '```heart.csv```' (available [here](https://drive.google.com/drive/folders/1Sgv7ghbh9Z1DDztioCd_zMmYpVTV9woJ)) is in the Colab path. Upload it to your runtime using the folder icon on the left-hand side menu bar. Or, you may upload it to your Google Drive and [link Drive to Colab](https://towardsdatascience.com/different-ways-to-connect-google-drive-to-a-google-colab-notebook-pt-1-de03433d2f7a).
1. Download the `Group31_HDSVM.ipynb` file to your local machine.
2. Open Google Colab in a browser.
3. Use the menu bar to navigate to File -> Open (alternatively, use the keybind Ctrl + O).
4. Select the "Upload" tab in the prompt and follow the instructions to upload `Group31_HDSVM.ipynb`.
### If you are running the experiment on a Jupyter notebook server
The procedure is similar, but you will have to download the dataset to the same directory as the notebook.
1. Download the `Group31_HDSVM.ipynb` file to the directory where the Jupyter notebook server is running from (or any other directory accessible to the client). 
2. Download the `heart.csv` file from [here](https://drive.google.com/drive/folders/1Sgv7ghbh9Z1DDztioCd_zMmYpVTV9woJ) to the same directory.
3. Locate the file in the Jupyter notebook client and open it.
4. Comment out the first (and only) line of cell 3. Or, delete it altogether.
### How to observe the results
1. On a fresh Jupyter kernel, run all the cells of the notebook.
2. Ignore the divide-by-zero warnings, those calculations are dropped.
3. Scroll to the bottom of the notebook. The salient results are displayed in the last few cells.
4. If you want to play with the hyperparameters (which we do a grid search for in the report),
	5. Find the cell with the lines of code
	 ```def print_report(X_train, y_train, X_test, y_test, kernel):``` 
	 ```		C_opt, acc, degree_opt, gamma_opt = get_optimal_C(X_train, y_train, kernel=kernel)```
	 and replace ```get_optimal_C(X_train, y_train, kernel=kernel)``` with your desired $C$, 0, $d$ (polynomial kernel degree) and $\gamma$ (radial basis function inverse-variance).
	 
Feel free to raise an issue on the repository if you have any trouble reproducing.
