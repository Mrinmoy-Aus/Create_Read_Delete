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
### Install Packages
> pip install -r requirements.txt

### To run the model:
> python crud.py

### Screenshots

### Basic UI
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/ui.png">

### 1. Open a file:
> In this module we have to open one existing file in which the Create,Read and Delete operations will be done.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/open.png">

### 2. Save a file:
> In this module we can save a new file or if not specified it will be stored in the default project directory.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/save.png">

### How it works? See:)
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/output.gif">

### 3. Create:
> In this module an user can insert key value pair in the database.The key is a string capped at 32kb and value is a json object capped at 16kb.The system throws proper error message for duplicate keys also.This module also supports time-to-live property if specified it will retain for the said time in the data store or else it will assume it to be infinite time if not specified.
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/create.png">
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/duplicate_error.png">

### How it works? See:)
<img src="https://github.com/argho28/Create_Read_Delete/blob/main/output.gif">

### 4. Read:
> In this module an user have to specify the key for which the respective json value will be extracted from the database and displayed in the value field.The system throws proper error message if the key is not present in the data store. 
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/videoSurveilance.jpeg">
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/faceMask.gif">

### How it works? See:)
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/videoSurveilance.gif">

### 5. Facebook Matcher:
> In this module we take the picture of the criminal and then find the criminal in facebook by using open source platform selenium and then extract the information of the criminal including the facebook ID of the criminal. This module is quite efficient and fast.
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/detectCriminal2.jpeg">

### How it works? See:)
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/facebookMatch.gif">

### 6. Twitter Matcher:
> Here also we take picture of the criminal and then find the criminal in twitter by selinium and scrap the information of the criminal from her/his profile.

### How it works? See:)
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/twitterMatch.gif">

### 7.	Crime Prediction:
> In this module we use a linear regression machine learning algorithm to predict crime in near future dates. This module plots analytics to depict major crimes, district crime, 15 top crime, resolution of crime, each day crime, district vs crime category, each month crime. Our module plots the crime description, weapon used in a map.
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/crimeDetection.jpeg">

### 8. Violence Detection: 
> In this module we take a video as input and then analyse the video and find out the frame where we have a gun shooting and crop the face of the criminal in the picture.
<img src="https://github.com/argho28/RK308_SmartCreators/blob/master/violenceDetection.jpeg">
