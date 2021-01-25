# USER MANAGEMENT API with JWT (Express, Mongodb)
## Deployed on [https://usermanagementapi.herokuapp.com/](https://usermanagementapi.herokuapp.com/)

### Features

- Create user (admin)
- GET all users (admin)
- GET single user by id (admin)
- UPDATE single user by id (admin)
- DELETE single user by id (admin)
- GET user profile (login user)
- UPDATE user profile (login user)
- Login

## Usage

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET_TOKEN = your jwt secret key
```

### Install Dependencies

```
npm install

```

### Run

```
# Run
npm start

# Run with nodemon
npm run dev
```

### Seed Database

Add an admin user manually to database

```
name <STRING>
email <STRING>
password <STRING>
isAdmin <BOOLEAN>
```

### Import 'postman-collection.json' to your postman

Import the json file and then you can test all the route.
