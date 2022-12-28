# Student-Enrollment-Form
## Description 
This is a web based html form for student enrollment using JsonPowerDB as Database 
JsonPowerDB is used to perform CURD operation 


# Benefits of using JsonPowerDB
* Simple to use , real time database
* Simplest way to retrieve data in a JSON format.
* Backends code is not required for database 
* No need for defining schema 
* Querying the database is easy there is no need  of knowledge of SQL commands

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

# Screenshots:
![Screenshot (7)](https://user-images.githubusercontent.com/95403606/209806270-d287e763-b99d-4945-a100-d5d5178ae7c8.png)

![Screenshot (8)](https://user-images.githubusercontent.com/95403606/209806277-2d0447e7-706b-4e98-a2ef-6fe8eab4f7b2.png)

# Illustrations:
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**

![Screenshot (7)](https://user-images.githubusercontent.com/95403606/209806383-02a7156f-baa8-434c-a441-e3c4e0934dc6.png)

We need to enter a roll number 

If roll number is not valid 

![Screenshot (9)](https://user-images.githubusercontent.com/95403606/209806520-7f8a08f7-b363-416c-bb91-2756d97cb667.png)

If roll number is valid and that roll number is existnig in database

![Screenshot (10)](https://user-images.githubusercontent.com/95403606/209806631-375b0b81-8fba-45fb-8774-ce19daf4d835.png)

* **Fetching student data using roll number**
  If student already present in database, then all field filled with that student information
  
  ![Screenshot (10)](https://user-images.githubusercontent.com/95403606/209806688-db2b5211-329f-4851-b4e8-e1dccbed20ec.png)
  otherwise, other fields are enabled after user input roll number
  
* **Updation of student details**
  In order to update student details input roll number, and then we can update the student data
 
  ![Screenshot (11)](https://user-images.githubusercontent.com/95403606/209807426-297f663f-1002-4a34-a18d-33bdc4cb88e4.png)
  
  ![Screenshot (12)](https://user-images.githubusercontent.com/95403606/209807466-3d8e60eb-347c-477e-bb00-2b8bf28c3660.png)

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid
  
  <img src="./images/save_data_1.png">
  
  <img src="./images/alert_after_save_data.png">
  
 * **If input data is not valid**
 
   <img src="./images/invalid_details_1.png">
  
   <img src="./images/invalid_details_2.png">

    
  
  # Installation
  
  Make a folder in your system and clone the project using git bash then open the project in Visual Studio Code or any IDE you prefer.
  ##### Clone the project 
  ```
  git clone https://github.com/prashant-smart/Recommendation-system.git
  ```
  After cloning 
  
  Move to **public_html** and then **script** folder and in **script.js** file replace the **connectionToken** by with your Connection Token
  
  # Sources
  * Introduction to JsonPowerDB - V2.0 course  on https://careers.login2explore.com/
  * [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 
  

  # Demo
  
  https://user-images.githubusercontent.com/72729279/209667623-a34280bf-97cd-4eae-9584-b5022ea194bc.mp4
  

  --------------------
## Hope You Like the Project ❤️❤️❤️
## Peace to everyone 🙏🏻
