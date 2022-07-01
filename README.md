<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="[https://github.com/rzmk/simple-blog](https://github.com/sidchopra13/Blog-Gen)">
    <img src="public/img/logo.jpg" alt="Blog-Logo" width="125" height="125">
  </a>

  <h3 align="center">Blog-Gen</h3>
  <div align="center">
    <a href="https://stormy-sands-79797.herokuapp.com/"><strong>View the blog here! »</strong></a>
    <br />
  </div>
</div>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#description">Description 🖋️</a>
      <ul>
        <li><a href="#technologies">Technologies 🛠️</a></li>
      </ul>
    </li>
    <li><a href="#how-to-deploy">How to Deploy? 🚀</a></li>
    <li><a href="#inspiration">Inspiration💡</a></li>
    <li><a href="#whats-next-for-blog-gen">What's next for Blog-Gen 🙌</a></li>
    <li><a href="#contact">Contact 😎</a></li>
  </ol>
</details>

<!-- Description -->
## Description

Hey! Welcome to Blog Gen! This is just a blog web application I built from learning how to develop full-stack applications. 
I was able to learn how the front-end and back-end interact along with a database, and it's turned out very well!

This web app uses Node.js for backend. I have used Express.js for serving static files, using middlewares and generating URL's for blogs with routes. The main part of the app is based on EJS, which is a template engine. As soon as you publish the blog, it gets saved on the MongoDB database with Mongoose and a new `div` is generated for your blogs. A new URL is also generated, as `/posts/your-title` by which you can access your blog. The compose blog page can be found at `/compose/`. All the blogs are saved on a MongoDB database, which is served with MongoDB Atlas service. All these CRUD operations are carried out on MongoDB with Mongoose.

<!-- Technologies -->

## Technologies

- ### [Node.js](https://nodejs.org/en/)
  A  JavaScript runtime built on v8 engine.

- ### [Express](http://expressjs.com/pt-br/)
  A Node.js web application framework that provides a robust set of features for web and mobile applications.

- ### [MySQL](https://www.mysql.com/)
  The most popular relational database.
  
- ### [EJS](https://ejs.co/)
  A templating language that lets you generate HTML markup with plain JavaScript.
  
- ### [Bootstrap](https://getbootstrap.com/)
  The world’s most popular framework for building responsive, mobile-first sites, with BootstrapCDN and a template starter page.

<!-- How-to-Deploy? -->
## How to Deploy? 

You can try out Blog-Gen by going here: **<a href = "(https://stormy-sands-79797.herokuapp.com/)" target = "_blank">(https://stormy-sands-79797.herokuapp.com/)</a>**<br>
If your want to try this app on your local machine, follow these steps: 
1. Clone this repository in your local environment by the following command:<br>
```git clone https://github.com/sidchopra13/Blog-Gen.git```

2. Use NPM (Node Package Manager) to install dependencies for this project. <br>
```npm install```

3. Use MongoDB Atlas service to set up your database on the cloud.

3. Use a `.env` file for storing the url containing username and password of your MongoDB Atlas database. The variables for these are: <br>
`MONGO_URL`

3. Now use Node.js to start the chat application: <br>
```node app.js```

4. Go to `localhost:3000` on your browser. This is the homepage of Blog-Gen. You can read blogs from here and click `Read more` to, well, read more!

5. Now you can go to the Compose button to publish your own blog. Your blog will be visible on the homepage, where you will also find a link to the dynamically created page and URL for your blog.

<!-- Inspiration -->
## Inspiration
This project was initially started as a course-along project which I made to learn Node.js and Express.js

<!-- What's next for Blog-Gen -->
## What's next for Blog-Gen 
Improving UI is the next step for this application. You can expect register and login functionality in next version of this web application. I would also like to hear any reviews, feedback or suggestions from you!

<!-- CONTACT -->
## Contact 

Siddharth Chopra - [@sidchopra49](https://twitter.com/sidchopra49)

Project Link: [https://github.com/sidchopra13/Blog-Gen](https://github.com/sidchopra13/Blog-Gen)
