﻿# Assignment
# Assignment-ORU

# User API Documentation

This documentation provides information about the User API endpoints and their usage.



## Get All Users
This endpoint retrieves all users from the database.

### Request
GET /users/vs

The UserModel.find() function is used to retrieve all documents from the UserModel collection in the database.
The retrieved users are then sent as a response using res.send(users).

