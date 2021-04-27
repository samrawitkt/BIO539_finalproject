# BIO539_finalproject

Title: Descriptive analysis of the effects of cultural cognition and racial background on the performance of a student

The BIO101_project was uploaded to the dataset repository and got loaded into the jupyter note book using the pd.read_excel(), following this path 
(“../BIO539/BIO101_project.xlsx”)

-To make our life easier in calling column names, the data was tied by changing column names into shorter versions. 
-Further the data columns with numerical values and significance to our study were cleaned by removing null values using dropna method of the pandas package. 
-To investigate the effect of background on the student performance we grouped by Ethnicity and applied statistical summary on the grouped data on the DigEx values.
-Similarly to get a clear indication of the gap between members of the same ethnicity, we manipulted to get the maximum and minimum scores of each ethnicity in the DigEx.
-The two manipulation were presented in a graphical interpretation to give visual representation. 
-Linear regression model was employed to test the interactions between different attritbutes of the dataset. The regression tables are reported and statistical significance of these data are reported based on their p-values. Resudual test for the regressional models was also performed to test the robustness of the model. 
-A prediction attept was made based on program choice and first exam results to see how program of study influences students' performance.  
