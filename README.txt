
Libraries needed for running the code below:
numpy, tables, pyspark, hdf5, gmaps, matplotlib (for conversion)

I have provided 3 .ipynb files, along with the .csv file obtained for the sample subset of data (10,000) records. --> Sample records.csv
I haven't atached the csv file for the final data because of it's large size

The complete data is available on the website provided in the report


1. MSD_Pandas_Subset  --> Used Pandas on the subset data and answered the 3 questions
2. MSD_Spark_Subset  --> Used pyspark on the subset data and answered the 3 questions
3. MSD_Spark_Final  --> Used pyspark on the Complete Dataset and answered the 3 questions


Conversion files
1. The compressed .zip file CSV_Converted_files has the 2 python files: hdf5_getters.py and msdHDF5toCSV used for conversion 
2. It also has a csv file SongCSV.csv which is the same as Sample records.csv


MobaXterm was used for accessing the Amazon cluster








Other files include the report file(.docx and .pdf format)