# Extract-Transform-Load-Log

## Objective
To understand flow of ETL

## What is ETL ?

ETL stands for extract, transform, load is a three phase process where data is brought from multiple sources, cleaned and stored into data warehouse or target system.

## Module Imported

In this simple project, module used are: <br>
1. glob : It helps in selecting files  
2. pandas : It helps in processing csv and json files
3. xml.etree.ElementTree  : It helps in processing xml files
4. datetime : For the extractraction of current date and time

## Function Creation

1. Extract Function : Data extracted from multiple file format : csv, json, xml
2. Transform Function : Simple mathematical conversion is done
3. Load Function  : Analysis ready data loaded to targeted file
4. Log Function : Keep track of events happened

## Note
Firstly, necessary data is accessed by mounting the drive to colab and used files are attached above. <br>
Secondly, instead of storing log function data to logfile.txt, it is printed in the output to show the result on point
