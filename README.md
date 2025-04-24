# CapstoneFinal
This repository contains the source code and .exe files required for the submission of my final project in the capstone class.

# UI
This is the client-side UI Application. Users will download the .zip file and run the executable to use the application. This application includes but is not limited to:
* Login/Registration
* Order Management
* Station Layout Management
* Edit Orders
* View Performance Analytics

The .zip file with the .exe can be found in this repo.

# API
This is the API which serves the application. While these files are included there is no need to download and run them because this API as well as the Database is running in Azure cloud. This is a RESTful API is built in .NET Core.

#FakePOS
This is the app used to test the KDS system. It provides the system with fake orders. To use this, you must have access to the ID of the user to whom you wish to send an order. This can be found using MySQL Workbench, or tested by using the test account (Username:admin, Password:admin, ID:0)
