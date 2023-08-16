# BookMyShow API
The project involves using NodeJS with express to build APIs for a movie booking application, We have named it BookMyShow. 

We have exposed two endpoints as per the requirements of the project, 

**/api/booking** **:method:GET** : Will retrieve the last booking details from the MongoDB BookMyShow collection and send it to the client with 200 status code
**/api/booking** **:method:POST** : Will create a booking document  in the MongoDB collection after schema validation and send 200 status to the client for success and 400 status code incase of failure 

According to the guidelines given for the CapStone project, we must develop a backend API that will deliver responses in JSON format, utilizing modular coding that uses separate files for each api connection, a separate file to handle the database and an app for all routes.

 ## directory💠
 - **/src/app**- Contains the code for mongoDB atlas connection and app spawning
 - **/src/Models**- Contains the Schema.js file which holds the schema for the Booking object for mongoDB
- **/src/Routest**- Contains the Routes.js file which holds the code to the API endpoint routes


## Reflection💠

- This project gave me a beautiful insight about the insight about the intricacies involved with backend the communication process with the front-end, learnt many other things along the way like JWT authentication and authorization(not implemented in this project).

## Built with
<img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" height="25">
<img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" height="25">
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" height="25">

## Deployed on
<a href='https://render.com/' ><img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"  height="25"></a>


## Resources Used

- Knowledge of Node, Express js and MongoDB.
- Mongoose Docs.