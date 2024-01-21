# ANTIQUE SHOP
Stack: MongoDB,React, Express.js, Node.js
## Setting your own MongoDB cluster
As this project works in the MongoDB in cloud, it requires the user to use his own MongoDB connection string. You can get it for free on cloud.mongodb.com by creating a free cluster.

Then you need to edit config.js file and change value of mongoURI variable, that contains connection string.


## How to run it?
#### In one terminal window, use following commands:
##### cd backend
##### npm i
##### npm run dev
#### In another terminal window:
##### cd frontend
##### npm i
##### npm run dev

## Antique schema

### Condition of antique can only take values 'Excellent', 'Good', 'Fair', 'Poor'- important when creating etc.
