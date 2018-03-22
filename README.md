# Mapping_Data
## Mapping data dynamically populated on desired rows and columns
## Using MongoDb, Python, Flask

# Install MongoDB 3.2 V and have a DB created as the name in the script.
# Need to have python 2.6 V
# To run the project , we need to unzip the file and cd to the test directory. Then inside test we find app1.py file, just run the file using command python app1.py. Upon successful run we have to open the browser and browse to localhost with port 5000. 
# The project needs dependencies to be installed. There is a setup.py file which will install the dependencies before run or during compilation. If it does not then we need to download the libraries manually.
# We need to check if we have a directory “uploads” inside test directory. Right now we are not flushing the files after DB write. Need to work on that. Until then we need to empty the directory manually upon every new upload of files else it will just append the DB not overwrite. Same case with the collection in the DB.

This is a sample work in which our web page populates column names dynamically for any kind of csv or similar file saved in mongoDb and choose columns which is required and write to another CSV file.

