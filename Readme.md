#Sales Detection Using Training Model

In this project the training model is written in R programming Language so as to analyze and train model to perform operation of sales prediction for the sales over the year including Holidays. This helps store manangers to keep track of need of goods so as to meet customer requirements

##Steps to Install Project 

User Manual: 
1. First Install the R programming language into the system from the link provided below: 
http://cran.r-project.org/mirrors.html
 
2. Install the R Studio for windows, Linux or mac OSX from the website link below:
http://www.rstudio.com/products/rstudio/download/
 
3. After the installation copy the project folder into the system user documents folder example 
C: /Users/Administrator/MyDocuments.  

4. Open the R studio software installed into the system.
 
5. Select the target folder where the project is copied to the hard disk make sure the data folder
in the project folder contains all .csv dataset files 

6. Open project.Rproj file to load all the variables of the logic. 
 
7. Install the packages form the “Tools” in the toolbar by selecting Tools>>Install Packages
make sure the system have the internet connection to install the packages 
 
8. Type in the name of the packages required to install “TimeDate,RandomForest” both the
packages must be separated by comma “,”. Repository must be set to CRAN for installation. 

9.Check whether the installation is done properly from the output window console in the R studio

10.Open the code file from the R folder named Logic.R  

11. Run the code in the file by selecting all code by CTRL+A and then run it by pressing Enter. 

12. The output screen will calculate the proximity values into the output windows. 
      Note: The program may take 5 minutes to execute.

13. The output console window will show that the final output is written into the Final.csv file 
into the final folder of the project.
 
14. Go to this final file from the explorer and open the Final.csv into the Excel. This file will 
show the predicted outcome of the sales for the future dates.
 
15. Possible error may occur when the path of the dataset files are not properly set or package is
not installed properly. Solution is to check the path of the dataset all the .csv files and change
into the input section of the program to read the data and re-installation of packages from the
step 7. 

