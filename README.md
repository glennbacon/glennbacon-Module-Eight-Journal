# glennbacon-Module-Eight-Journal

CS 340 README


About the Project Create and Read in Python
The project is to provide functionality in order to develop a web application that connects a client-side user interface to a database. This is a portable Python module that has Create and Read functionality and connectivity to Mongodb database.

Motivation
This project exists to glue a Mongodb database and a user interface together for Project One and it is also part of assignment Module 4 for CS-340 SNHU course.

Getting Started
To get a local copy up and running, follow these simple example steps:
In the module4.py file change username, password, port_number and database_name to your Mongodb credentials.
self.client = MongoClient('mongodb://username:password@localhost:port_number/database_name')

Installation
List of tools you will need to use this software:
•	Python 3 information to download and install are at https://www.python.org/ 
•	Jupter Notebook is used to test and run the test_module4.ipynb download and install from https://jupyter.org/ 
•	Mongodb is database software and can be downloaded and installed from https://www.mongodb.com/ 
•	Pymongo is a tool to interacting with MongoDB database from Python https://pypi.org/project/pymongo/ 

Usage

Code Example
Initialize and connect to the database.
animal = module4.AnimalShelter()
Create and insert a new animal document into the database.
animal.create(data)
Query and return all documents in a list.
animal.read(data)
Tests
To run and test this module make sure to update module4.py connection settings that are shown in the getting started section of this README above. To run a test simply open the test_module4.ipynb in Jupyter Notebook. The test should run automatically if it does not click the Run button. A successful test will return True and show input and output data of the test. A failed test will return False and may also show other errors if exists.


Contact
Glenn Bacon
