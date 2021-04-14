# YelpCamp

YelpCamp is a website where users can create and review campgrounds.
In order to review or create a campground, you must have an account.
This project was created using Node.js, Express, MongoDB, and Bootstrap.Passport.js was used to handle authentication.

![app demo](yelpcamp.gif)


## Advantages:

- Users can create, edit, and remove campgrounds.
- Users can review campgrounds once, and edit or remove their review.
- User profiles include information of the user (full name, email), their campgrounds, and the option to edit their profile or delete their account


## To Run It Locally:
- Install mongodb.
- Create a cloudinary account to get an API key and secret code.
- git clone https://github.com/bhumikakr/YelpCamp.git
- cd yelpcamp
- npm install
- npm -init 
- Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

```SECRET=
CLOUDINARY_CLOUD_NAME= 
CLOUDINARY_KEY= 
CLOUDINARY_SECRET=
DB_URL=
```
- Run mongod in another terminal and node app.js in the terminal with the project.
- Then go to localhost:3000.
 
## Others:
 
 **Click on this link to see my version deployed on heroku:https://morning-lake-75784.herokuapp.com/**
