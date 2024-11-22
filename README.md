# data-sourcing-challenge
## Module 6 Homework Assignment
### Table of Contents
1. **Program Description**
2. **File Structure**
3. **How to run the notebook**
4. **README.md**
5. **example.env**
6. **retrieve_data.ipynb**
7. **output**


## 1. **Program Description**

This notebook will prepare a dataset for a prediction system that will help the NOOA Space Weather Prediction Center predict Geomagnetic Storms (GSTs).

These storms are caused by so-called Coronal Mass Ejections (CMEs), which are a massive bursts of plasma emitted from the Sun in irregular intervals, that Earth's magnetic shield fortunately renders harmless to us. However, this interaction with the magnetic shield can still create so-called Geomagnetic Storms (which also cause the Northern and Southern Lights) that can be harmful to electronic devices such as satellites, GPS systems, and essential parts of our powergrids.

NASA and the Space Weather Prediction Center operate a number of measuring satellites that collect data on CMEs. This data is then used to warn powergrid operators and GPS system operators ahead of time, so that they can make necessary adjustments.


## 2. **File Structure**

![Repo Image](<Screenshot 2024-11-22 at 5.24.21 PM-1.png>)

## 3. **How to run the notebook**

Within VS Code, select the **"retrieve_data.ipynb"** file and execute each of the code cells within the notebook from top to bottom in order.


## 4. **README.md**

This file. 


## 5. **example.env**

This file contains your NASA API Key needed to make queries from the NASA website. Rename the file to **.env** after you enter your proper API Key. 


## 6. **retrieve_data.ipynb**

This notebook contins the various code cells that will cover the following:

1. CME Data - Import the data using proper API Key and create a DataFrame with the relavent pieces of information needed to do the analysis.
2. GST Data - Import the data using proper API Key and create a DataFrame with the relavent pieces of information needed to do the analysis.
3. Merge Both Datasets - Merge the CME and GST datasets.
4. Compute the Time it Takes for a CME to Cause a GST - Calculate the time difference between these two events. 
5. Export the Data to a CSV format file - Export the results into a file. 


## 7. **output**

This folder contains the results from the notebook.

1. collected_data.csv


---------------------------------------------

Mark Murphy mmurphy2k@gmail.com
