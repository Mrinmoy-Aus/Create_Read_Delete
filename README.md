<img src="https://www.spirit-of-metal.com/les%20goupes/C/Crud/pics/781097_logo.jpg">

# Create Read and Delete Operations

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)   

### Contributor
<a href="https://github.com/argho28"><img src="https://avatars3.githubusercontent.com/u/54744863?s=400&v=4" height="50px" width="50px" alt=""/></a>



### Code Requirements
>numpy==1.19.1(pip install numpy)</br>
>XlsxWriter==1.3.7(pip install XlsxWriter)</br>
>pandas==1.1.5(pip install pandas)</br>
>openpyxl==3.0.5(pip install openpyxl)

### System Requirements
> Os supported: Ubuntu 18.04.5 LTS, windows 10, windows 8</br>
> Ram: 4GB</br>
> Space: 205.9 kB</br>

### Install Packages
> pip install -r requirements.txt

### Testing
- [x]  Modules tested unit by unit
- [x]  Checked on different OS
- [x]  Thread safe supports multiprocessing

### To run the model:
> python crud.py

### Screenshots

### Basic UI
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/ui.png">

### 1. Open a file:
> In this module we have to open one existing file in which the Create,Read and Delete operations will be done.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/open.png">

### 2. Initialize:
> In this module we can save a new file or if not specified it will be stored in the default project directory.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/save.png">

### How it works? See:)
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/output.gif">

### 3. Create:
> In this module an user can insert key value pair in the database.The key is a string capped at 32chars and value is a json object capped at 16kb.The system throws proper error message for duplicate keys also.This module also supports time-to-live property if specified it will retain for the said time in the data store or else it will assume it to be infinite time if not specified.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/create.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/duplicate_error.png">

### 4. Read:
> In this module an user have to specify the key for which the respective json object will be extracted from the database and displayed in the value field.The system throws proper error message if the key is not present in the data store.This module also supports time-to-live property and does not allow read operations if the record has expired and proper messages are also generated for the said property. 
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/read.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/read_error.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/time-to-live.png">

### 5. Delete:
> In this module an user have to specify the key for which the respective value has to be deleted.The system throws proper error message if the key is not present in the data store.This module also supports time-to-live property and does not allow delete operations if the record has expired and proper messages are also generated for the said property.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/delete.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/delete_error.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/time-to-live.png">

### 6. Show:
> This module extracts all the information from the database and makes it visible in a tabular format to the user.This module also supports time-to-live property and does not retain the records whose specified time limit has expired.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/show.png">

### 7.	Clear:
> This module clears all the data present in Key,Value and Time-to-live input fields respectively.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/clear.gif">
