# Pymongo
Connect Mongo Database with python code
Connect to MongoDB Database
 In order to connect with MongoDB database through python application, a driver software is required.
 To install python Driver for MongoDB use “python –m pip install pymongo”
 Through this driver CRUD operations can be performed.
 In python, pymongo is used to establish connection with mongo.
 Data can be retrieved or inserted into database by using pymongo.
 Import MongoClient from pymongo.
• Specify the database url in MongoClient().
• Specify the name of the database using “client.” For example, “client.demo” is used to connect with database named “demo.”
• Use “db.collection.find()” method to get all the documents stored in the database.
 To insert data in the database, insert_one() method can be used.
• Data passed to this method will be added to the database.
