# hotornot

Image File compare tool.

## Requirements

* [Node](https://nodejs.org/en/download/)
* [Git](https://git-scm.com/downloads)
* [Mongodb](https://www.mongodb.com/download-center/community)


## Setup 

#### Step 1: Clone the repo

```bash
git clone git://github.com/cksachdev/hotornot.git
```

#### Step 2: Use below command to install all required dependencies

```bash
npm install
```

#### Step 3: Run the mongodb locally
If you don't know how to start the mongodb locally don't worry Please refer a link below for your reference
[https://docs.mongodb.com/v3.2/administration/install-community/](https://docs.mongodb.com/v3.2/administration/install-community/) 

And Install mongodb compass (MongoDB Compass is the GUI for MongoDB. Compass allows you to analyze and understand the contents of your data without formal knowledge of MongoDB query)

To install mongodb compass use this link: 
[https://www.mongodb.com/products/compass](https://www.mongodb.com/products/compass)

#### Step 4: Set the database path 
```
// dbConnection.js 

const DB_PATH = '';

```

#### Step 4: To start the local server
```
node server.js
```
Then visit [http://localhost:3000/](http://localhost:3000/)
