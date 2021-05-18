# blogly-backend
Blogly is a simple but slick looking, full stack, blogging web application. This repo contains the Node.js/Express.js back-end component of Blogly. Front-end code can be accessed **[here](https://github.com/alexgenc/blogly-frontend)**.

Live Demo: https://phobic-soda.surge.sh/

## Introduction 
The back-end includes a classic RESTful API setup for /api/posts route. It's used for creating new blog posts, updating existing posts, deleting existing posts, and upvoting and downvoting posts. 

Similarly /api/posts/:post_id/comments also has a RESTful API setup for handling comments on each blog post.

Back-end can be accessed using the following link: https://alexgenc-blogly.herokuapp.com/ 

## Routes

- /api/posts 
- /api/posts/:post_id/comments

## Database

Back-end is connected to a PostgreSQL database. All posts related information is stored in the database.
