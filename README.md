# Tech Blog


## User Story
As developer who writes about tech, user wants a CMS-style blog site, so that they can publish articles, blog posts, and their thoughts and opinions.

## Table of Contents 
1. [About the Project](#About-The-Project)
1. [Project Links](#Project-Links)
1. [Homepage Screenshot](#Homepage-Screenshot)
1. [Installation](#Installation)
1. [Contribution Guidelines](#Contribution-Guidelines)


## About The Project
Given a CMS-style blog site: 
- When user visits the site for the first time, they are presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.
- When user clicks on the homepage option, they are taken to the homepage.
- When user chooses to sign up, they are prompted to create a username and password.
- When user clicks on the sign-up button, the user credentials are saved and user is logged into the site.
- When user revisits the site at a later time and choose to sign in, they are prompted to enter my username and password.
- When user is signed in to the site, they can see navigation links for the homepage, the dashboard, and the option to log out.
- When user clicks on the homepage option in the navigation, they are taken to the homepage and presented with existing blog posts that include the post title and the date created.
- When user clicks on an existing blog post, they are presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment.
- When user enters a comment and clicks on the submit button while signed in, the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.
- When user clicks on the dashboard option in the navigation, they are taken to the dashboard and presented with any blog posts that have already created and the option to add a new blog post.
- When user clicks on the button to add a new blog post, they are prompted to enter both a title and contents for the blog post.
- When user clicks on the button to create a new blog post, the title and contents of the post are saved and user is taken back to an updated dashboard with the new blog post.
- When user clicks on one of the existing posts in the dashboard, they are able to delete or update a post and taken back to an updated dashboard.
- When user clicks on the logout option in the navigation, they are signed out of the site.
- When user is idle on the site for more than a set time, they are able to view comments but user is prompted to log in again before they can add, update, or delete comments.


## Project Links
[Repo Link](https://github.com/Sadegh777/tech_blog) <br>
[Deployed Project](https://techblogch.herokuapp.com/)

## Homepage Screenshot
![Homepage](assets/homepage.png)


## Instructions
```  
git clone https://github.com/Sadegh777/tech_blog.git
In the root directory of the project, run 'npm i' to download the dependencies.
Initiate the database with 'mysql -u root -p'.
To create tables, run 'source db/schema.sql'.
Exit the mysql terminal, and run 'npm run seed' to insert data into the tables.
Run 'npm start' to start your server.
```
Make sure to add a .env file to the root of the app with the following details:
```
DB_NAME='tech_blog_db'
DB_USER='user'
DB_PW='password'
```

#### Note: follow [this](https://flaviocopes.com/mysql-how-to-install/) to install MySql and setup your own username & password

## Languages and libraries used in this project:
- <a href="https://www.npmjs.com/">NPM</a>
- <a href="https://nodejs.org/">Node.js</a>
- <a href="https://www.npmjs.com/package/mysql2">MySQL2</a>
- <a href="https://sequelize.org/">Sequelize</a>
- <a href="https://www.npmjs.com/package/express">Express.js</a>
- <a href="https://www.npmjs.com/package/inquirer">Inquirer.js</a>

## Contribution Guidelines:


[Sadegh.M](https://github.com/Sadegh777) <br>
