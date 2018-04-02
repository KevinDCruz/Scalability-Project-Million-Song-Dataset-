
Libraries needed:
Pandas, NumPy, pytables, PySpark, hdf5, gmaps, matplotlib (for conversion)

I have provided 3 .ipynb files, along with the .csv file obtained for the sample subset of data (10,000) records. --> Sample records.csv

1. MSD_Pandas_Subset  --> Used Pandas on the subset data and answered the 3 questions
2. MSD_Spark_Subset  --> Used pyspark on the subset data and answered the 3 questions
3. MSD_Spark_Final  --> Used pyspark on the Complete Dataset and answered the 3 questions


Conversion files used to obtain the .csv

hdf5_getters.py and msdHDF5toCSV used for conversion, forked Repo: https://github.com/KevinDCruz/Million-Song-Dataset-HDF5-to-CSV



MobaXterm was used for accessing the Amazon cluster

Used AWS to work on the complete Dataset:

AWS EC2 Cluster: c4.2x large (8 cores, 15GB RAM), detailed mentioned in the report (CIS 602 Final Project Report_Kevin D'Cruz.pdf) 
