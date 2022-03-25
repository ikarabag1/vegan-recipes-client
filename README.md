# P3 PITCH
- I would like to build vegan recipes app for people who chooses vegan life style to have exclusive part in this communityso they can create, edit and experiment new recipes and search for other users recipes and leave reviews/notes under each recipe as they like.

# User Stories
- As a user I would like to; 
- register to create an account and able to delete my accout.
- login and logout of my account.
- create, delete my vegan recipes in my profile.
- have a home page that would display all recipes in the server.
- have a profile page where I could edit my name, profile picture.
- see a each recipe, pictures, descriptions and add it to favorites.
- able to write reviews and edit them for each recipe.

# Tech stach:
- Javascript
- CSS/Bootstrap
- React.js
- express
- MongoDB
- Mongoose

# Requirements:
MongoDB
NPM
Vegan-Recipes-Server

# ERDs 
![Wireframes](public/wireframes/userschema.png)

# Wireframes


# MVP goals
- creating a Mern app using ReactJS ca nbe usable by many users;
- can create recipes, make comments and edit all.
- can display other recipes and added to favorites and make reviews.
- edit or delete profile.


# Stretch Goals
- add music or more visual stuff

# Authentication
| VERB   | URI Path                    |CRUD           | Description                                        |
|--------|----------------------------------------------|---------------------------------------------------|
| POST   | `/register`                 |Create          | sign up / registration page                       |
| POST   | `/login`                    |Read            | login page -- findUser                            |
| GET    | `/profile`                  |Read            | displays user profile page                        |
| PUT    | `/profile/:id`              |Update          | updates user profile                              |
| DELETE | `/profile/:id`              |Destroy         | deletes profile                                   |

# Routes
| VERB   | URL Path                    |CRUD           | Description                                        |
|--------|----------------------------------------------|---------------------------------------------------|
| GET    | `/`                         |Read            | Home                                              |
| GET    | `/recipes`                  |Read            | displays recipes                                  |
| GET    | `/recipes/:id`              |Show            | display the specific recipe                       |
| POST   | `/recipes`                  |Create          | create a new recipe                               |
| PUT    | `/recipes/:id`              |Update          | update the recipe created by user                 |
| DELETE | `/recipes/:id`              |Destroy         | removes the recipe user created                   |
| POST   | `/:recipesId/notes`         |Create          | add review or a note to specific recipe           |
| PUT    | `/:recipesId/notes/:id`     |Update          | edit the reviews or note inserted in a recipe     |
| GET    | `/:recipesId/notes`         |Read            | displays recipe notes                             |
| DELETE | `/:recipesId/notes/:id`     |Destroy         | delete the note user inserted in a recipe         |
