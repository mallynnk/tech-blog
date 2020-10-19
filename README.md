# Tech Blog

## Table of Contents
  - [User Story](#user-story)
  - [Description](#description)
  - [Screenshots](#screenshots)
  - [Deployed Application](#deployed-application)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Contributing](#contributing)
  - [Questions](#questions)


## User Story
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

## Description
A blog using a mysql database, built using Model View Controller (MVC) paradigm. Built using MySQL2, Express, Sequelize, Bulma, Handlebars and dotenv.

Given the CMS-style blog site, when the user visits the site for the first time, they are presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in. When the user clicks on the homepage option, they are taken to the homepage. When the user clicks on any other links in the navigation, they are prompted to either sign up or sign in. When the user chooses to sign up, they are prompted to create a username and password. When the user clicks on the sign-up button, the user credentials are saved and the user is logged into the site. When the user revisits the site at a later time and chooses to sign in, they are prompted to enter their username and password. When the user is signed into the site, they see navigation links for the homepage, the dashboard, and the option to log out. When the user clicks on the homepage option in the navigation, they are taken to the homepage and presented with existing blog posts that include the post title and the date created. When the user clicks on an existing blog post, they are presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a commen.

When the user enters a comment and clicks on the submit button while signed in, the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created. Whent he user clicks on the dashboard option in the navigation, then they are taken to the dashboard and presented with any blog posts they have already created and the option to add a new blog post. When the user clicks on the button to add a new blog post, they are prompted to enter both a title and contents for their blog post. When the user clicks on the button to create a new blog post, the title and contents of their post are saved and they are taken back to an updated dashboard with their new blog post. When the user clicks on one of their existing posts in the dashboard, they are able to delete or update their post and are taken back to an updated dashboard. When the user clicks on the logout option in the navigation, they are signed out of the site. When the user is idle on the page for more than a set time, they are automatically signed out of the site

## Screenshots

## Deployed Application

## Installation
`npm init`

`npm install sequelize`

`npm install mysql2`

`npm install dotenv`

`npm install express`

`npm install express-handlebars`

`npm install express-session`

`npm install connect-session-sequelize`

`npm install bcrypt`

## Usage
Run the following command at the root of your project.
`mysql -u root -p`

Enter your password when prompted.
Run `source db/schema.sql`

Run `quit`

Run `npm start`

View your page on localhost. 

## Testing
Tested can be done through Insomnia Core.

## Contributing
Mallory Korpics
