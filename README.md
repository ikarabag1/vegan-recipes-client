# VEGAN RECIPES APP
- An app for people who chooses vegan life style to have exclusive part in this community so they can create, edit and experiment new recipes and search for other users recipes and leave reviews/notes under each recipe as they like.

# User Stories
As a user I would like to; 
- register to create an account.
- login and logout of my account.
- create, delete my vegan recipes in my profile.
- have a home page that would display all recipes.
- have a profile edit page where I could udpate my password.
- see each recipe, pictures, descriptions.
- able to add notes or reviews.

# Tech stach:
- Javascript
- CSS/Bootstrap
- React.js
- express
- MongoDB
- Mongoose

# Requirements:
- MongoDB
- NPM
- Vegan-Recipes-Serever (API)

# ERDs 
![Wireframes](public/wireframes/userschema.png)

# Wireframes
![Wireframes](public/wireframes/routeswireframe.png)

# MVP goals
Building a Mern app using ReactJS can be usable by many users;
- can create a profile.
- can create recipes.
- can display all recipes on profile.
- can show specific recipe.
- can add a review to each recipe.



# Authentication
| VERB   | URI Path  | CRUD   | Description   |
| :---: | :--------: | :----: | :----------: |
| POST  | `/register` | Create | sign up/ user registeration |
| GET   | `/profile` | Read   | displays user profile page |
| GET   | `/login`   | Read   | login /find user |
| GET   | `/logout`  | Read   | logout user |

# Routes
| VERB  | URL Path  | CRUD  | Description  |
| :----: | :-----: | :----: | :--------: |
| GET    | `/`   | Read   | Welcome page   |
| GET    | `/recipes` | Read | displays recipes   |
| GET    | `/recipes/:id` | Show  | display the specific recipe  |
| POST   | `/recipes`  | Create  | create a new recipe  |
| PUT    | `/recipes/:id` | Update  | update the recipe created by user |
| DELETE | `/recipes/:id` | Destroy  | removes the recipe user created  |
| POST   | `/recipes/:id`  | Create  | add review or a note to specific recipe  |

# Strech goals
- editing comments.
- deleting comments.
- display other user recipes.
- able to add comments on other user recipes and delete.
- can edit password and delete account.
| PUT    | `/profile/:id`  | Update   | updates user password |
| DELETE | `/profile/:id`  | Destroy  | deletes profile    |

