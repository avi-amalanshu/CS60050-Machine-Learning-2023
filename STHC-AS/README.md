# Seed Type Determination Rating using Single Linkage Agglomerative (Bottom-Up) Clustering Technique (STHC-AS)
## Avi Amalanshu (20EC30063)
This project contains code for the project "Seed Type Determination Rating using Single Linkage Agglomerative (Bottom-Up) Clustering Technique (STHC-AS)". This is a part of the Machine Learning (CS60050) course offered at IIT Kharagpur in the Spring semester 2023.  The objective is to compare clusters detected by bottom-up, single linkage agglomerative clustering with those detected by k-means clustering. We see that the single-linkage strategy makes the performance susceptible to outliers.
### If you are running the experiment in Google Colab
The code is plug-n-play for Google Colab.
1. Download the `20EC30063_STHC-AS.ipynb` file to your local machine.
2. Open Google Colab in a browser.
3. Use the menu bar to navigate to File -> Open (alternatively, use the keybind Ctrl + O).
4. Select the "Upload" tab in the prompt and follow the instructions to upload `20EC30063_STHC-AS.ipynb`.
### If you are running the experiment on a Jupyter notebook server
The procedure is similar, but you will have to slightly modify the code.
1. Download the `20EC30063_STHC-AS.ipynb` file to the directory where the Jupyter notebook server is running from (or any other directory accessible to the client). 
2. Download the `seeds.csv` file from [here](https://drive.google.com/file/d/1BZrusNGN7DWfbqqshRRbGnvXaLHsXKIP/view) to the same directory.
3. Locate the file in the Jupyter notebook client and open it.
4. Comment out the first (and only) line of cell 3. Or, delete it altogether.
### How to observe the results
1. The following three steps can be ignored to reproduce the results of the report.
2. Set the initial value of $k$ by setting the value of `K_TEST` in the first cell.
3. Set the number of iterations for the $k$-means algorithm by setting the value of `ITER_KM` in the first cell.
4. Set the other candidate values of $k$ to check by adding them to the list of $i$ values in the 9th cell.
5. Run the interactive notebook.
6. The outputs appear in the 9th, 10th and 16th code cells. They are documented by the text cells.
