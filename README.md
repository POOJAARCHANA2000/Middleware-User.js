
MyWays-Nodejs-Backend-Task
I first created User Model for creating and reading documents from the underlying MongoDB database.

Some npm install libraries :

Express
body-parser
Mongoose
I used Postman to check all the APIs working perfectly. Operations that have checked on Postman.

Create(Create name,email,reviews)
Login/Logout(For User)
Delete(Delete an user)
Modify or Update(Edit all reviews)
I've used Schema Middleware for User Authentication using JsonWebToken Usually JsonWebToken has 2 operations for creating and verifying tokens.

jwt.sign({user.data},"String")
jwt.verify(token,"String")
