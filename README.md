# Blog App with React Node.js Express MySQL in javascript

This is a for a full stack Blog Application using React components on the front end, with a CRUD Application using NodeJS + Express + MySQL on the back end.

## Demo

### Home Page
<img width="582" alt="image" src="https://user-images.githubusercontent.com/67286396/234439050-2da14148-ae4c-4d76-a797-e7a0ddfe6473.png">

### Authentication Page
<p float="left">
<img src="https://user-images.githubusercontent.com/67286396/234437626-dbb2a7d2-de11-430b-a4ce-319ab17a1faa.jpg" width=40%>
<img src="https://user-images.githubusercontent.com/67286396/234437610-ac0b9b97-ca3e-4040-97c0-bb44dffd5484.jpg" width=40%>
</p>

### Compose Page
<img width="582" alt="image" src="https://user-images.githubusercontent.com/67286396/234438578-8510fd94-d457-4bde-af1e-f29441f2cffb.jpg">


## Structure
#### Client
- src: contains all the web page components
  * components: footer, menu, navbar
  * pages: home, login, register, write, post
  * img: logo, buttons
  * style: style.scss for customized design
  * context: user identification
- public: stores user uploaded images

#### Api
- index.js
- database: db.js
- controller/routes: to manage changes in database for authentication, posts, and users

In the project directory, you can run:

#### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### Package Required
Client Folder contains the Front End packages with React
    "react": "^18.0.0",
    "react-dom": "^18.0.0",
    "react-quill": "^2.0.0",
    "react-router-dom": "^6.10.0",
    "react-scripts": "5.0.1",
    "sass": "^1.62.0",
    "moment": "^2.29.4",
    "axios": "^1.3.6",

Api Folder contains the Back End packages with MySQL server
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "ejs": "~2.6.1",
    "express": "~4.16.1",
    "http-errors": "~1.6.3",
    "morgan": "~1.9.1"
    
** "nodemon" Helps in automatically restarting the server whenever the code changes.



  






