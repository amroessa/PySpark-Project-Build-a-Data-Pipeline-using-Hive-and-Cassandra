
#  Spark Integration with Hive and Cassandra
Spark can read and write data from anywhere.
# Why we need Integration
To fast data processing.

    
# Extract , Tansformation and Load 
To create data pipline we need ETL .

## PySpark Integration with Hive.

Read write table from Hive.

## PySpark Integration with cassandra.

Read write data from Cassandra.

#Note -
follow docker installation steps to integrate pyspark with hive

#Note-
For cassandra follow cassandra.txt file

# Code Description
    File Name : pyspark_hive.ipynb , pyspark_cassandra.ipynb, pyspark_hive.py and pyspark_cassandra.py
    DataSets : airlines1.csv
    File Description : Integration of pyspark with Hive and Cassandra.
    

#NOTE :- use findspark library when executing python script

 - import findspark
 - findspark.init()

## Steps to Run
There are two ways to execute the end to end flow.
 - Command Prompt => python script
 - spark_path spark-submit file_path
 - spark_path => <path_to_spark>>
 - file_path => <path_to_file>
 - Data file path is same as script file path

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\Integration\pyspark_cassandra.py>


- IPython

### Modular code
- Create virtualenv
- Install requirements `pip install -r requirements.txt`
- Run Code `python pyspark_hive.py`
- Run Code `python pyspark_cassandra.py`
- Check output for all the visualization
### IPython
Follow the instructions in the notebook `pyspark_hive.ipynb`
Follow the instructions in the notebook `pyspark_cassandra.ipynb`

 
