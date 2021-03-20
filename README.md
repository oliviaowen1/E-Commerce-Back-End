# E-Commerce-Back-End
## Table of Contents

* [Description](#Description)
* [Installation](#Installation)
* [Screenshots](#Screenshots)
* [License](#License)



# Description
The aim of this application is to build the back-end of an E-Commerce application.

This application uses an Express.js API to use Sequelize to interact with a MySQL database. 

The demonstration of this application uses Insomnia to carry out the functions requested.

# Installation 

You can see a video of the application fully functioning [here](https://drive.google.com/file/d/1bHfaYJeSPTsALYC1dcYpXFlCbtdkV96i/view)

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

The video begins by showing how to create the schema from the MySQL shell, this then shows you how to seed the database from the command line. It then goes on to show you how to begin the applications' server.

It then moves on to Insomnia where first it shows the GET routes for all categories, all products, and all tags.

From here you then see GET routes for a single category, a single product, and a single tag.

Finally the demonstration shows POST, PUT, and DELETE routes for categories, products, and tags.

 
# Screenshots


The screenshots below show the following:

When you send the GET request for "Get All Tags" this will return all the tags as below.
![get all tags](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/GET%20ALL%20TAGS.png)


You can also send a GET request for a specific ID, as seen below:

![get tags by id](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/GET%20ALL%20TAGS%20BY%20ID.png)


You can also create a tag using a POST request as you will see below:

![create tag](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/CREATE%20TAG.png)


And this is then reflected when you send a new GET request for "Get All Tags":

![updated all 1](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDTED%20GET%20ALL%20TAGS%201.png)


This can then be updated using a PUT request, in order to do this, you will need to enter the ID number you wish to update in the URL location, as below:


![update request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATE%20TAG.png)


This will then again reflect when you send a new GET request for "Get All Tags":


![updated get all](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATED%20GET%20ALL%20TAGS%202.png)


You can also delete a request, which again will require you to enter the ID you wish to delete into the URL and click send:


![delete request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/DELETE%20TAG.png)


As you can see below, this will then ammend and update on the next GET request for "Get All Tags"


![final get all request](https://raw.githubusercontent.com/oliviaowen1/E-Commerce-Back-End/main/Assets/UPDATED%20GET%20ALL%20TAGS%203.png)









# License
![license: MIT](https://img.shields.io/badge/License-MIT-blue.svg)