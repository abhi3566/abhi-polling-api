# Polling-System-API
 Polling System API created using NodeJS express and mongo
 
# Tech stack
- express: it is managing the frontend of this App
- Node: takes care of all the backend actions taking place.
- MongoDB: Managing all the data of this App.

## Technologies Used
1.  NodeJS
2.  Express
3.  MongoDB
4.  Mongoose

## Prerequisites
- Git
- NodeJS
- Rest API
- Postman

##### Into the project directory

`cd Polling System API`

##### Installing NPM dependencies

`npm install`


##### Then simply start your app

`npm start`

#### The Server should now be running at http://localhost:8000/

## Routes
- `GET /` For simple welcome message
- `GET /question/` For getting all existing questions
- `GET /question/:id` For getting a single question
- `POST /question/create` to create a question. Pass json data in body `{
    "title" : "test123"
}`
- `POST /question/:id/option/create` to create options for a question. Pass the question id in url id parameter and JSON data in body `{
    "options" : ["abc","def"]
}`
- `GET /question/:id/delete` to delete a question. Pass the question id in url id parameter
- `GET /option/` For getting all existing options
- `GET /option/:id/delete` to delete an option. Pass the option id in url id parameter
- `GET /option/:id/add_vote` to vote for an option.Pass the option id in url id parameter