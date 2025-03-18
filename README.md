# react-full-stack-blog-site

## Repository for my react-full-stack-blog-site project

Find out how to build an blog site platform. 

1. Methodologies/Project Management:

   - Agile

2. Coding Practices:

   - OOP (Object Oriented Programming)

3. Programming Languages/Frameworks:
   - JavaScript
   - React
   - NodeJS
   - Express
   - MongoDB
   - Postman


## Instructions

1. Make sure you have these installed

   - [NodeJS](https://nodejs.org/en/download/ "NodeJS")
      - I used LTS node version 14.15.1 and npm version 6.14.8 at time of creation
   - [MongoDB](https://www.mongodb.com/try/download/community "MongoDB")
      - I used mongo version 4.4.1 at time of creation
   - [Postman](https://www.postman.com/downloads/ "Postman")
      - I used postman version 7.36.0 at time of creation

2. Clone this repository into your local machine using the terminal (mac) or [Gitbash (PC)](https://git-scm.com/download/win "Gitbash (PC)")

   ```
   > git clone https://github.com/iammelvink/react-full-stack-blog-site.git
   ```

3. blog-site-frontend setup (running on port 3000)
   ```
   > cd blog-site-frontend
   ```

   ```
   > npm install
   ```

   Compiles and hot-reloads for development
   ```
   > npm run start
   ```

4. blog-site-backend setup (running on port 8000)
   ```
   > cd blog-site-backend
   ```

   ```
   > npm install
   ```

5. Insert data into the MongoDB database
   - Start MongoDB server
      ```
      > mongod
      ```

   - Enter mongo shell
      ```
      > mongo
      ```

   - Insert data into the MongoDB database
      ```
      > db.articles.insert([ 
         { name: 'learn-react', upvotes: 0, comments: [], }, 
         { name: 'learn-node', upvotes: 0, comments: [], }, 
         { name: 'my-thoughts-on-resumes', upvotes: 0, comments: [], }, ])
      ```

6. Compiles and hot-reloads for development
   ```
   > npm run start
   ```

7. Enjoy!


