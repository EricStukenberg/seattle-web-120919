# Sinatra RESTful Routes

| CRUD Letter | RESTful Route          | Controller Action |
|-------------|------------------------|-------------------|
| C(reate)    | POST   /books          | create            |
| R(ead)      | GET    /books          | index             |
| R(ead)      | GET    /books/:id      | show              |
| U(pdate)    | PATCH  /books/:id      | update            |
| D(elete)    | DELETE /books/:id      | destroy           |

## Students Will Be Able to:
 
 - [x] Explain the connection between HTTP methods and CRUD
 - [x] Explain the connection between HTTP URL paths and CRUD
 - [x] Implement server-side full CRUD in Sinatra
 - [x] Use Postman to test controller actions when the view code has not been completed

## Deliverables

 - [x] As a user, I should be able to view the information about a particular book by providing its ID
 - [x] As a user, I should be able to create a new book by providing form data (using Postman)
 - [x] As a user, I should be able to update an existing book by providing its ID as well as form data (using Postman)
 - [x] As a user, I should be able to delete an existing book by providing its ID (using Postman)

## Questions to Ask for Each Deliverable

1. What new model(s) do I need?
    - New class?
    - New migration? (i.e. does the schema need to change?)
    - Associations?
    - Seeds?
2. What route(s) do I need?
3. What controller action(s) do I need?
    - In Sinatra, this means the code directly below the route, but in Rails it will be a separate file
4. What view(s) do I need?

## Instructions for Getting Started

To run this application, use the following bash commands:

0. `cd` into this directory
1. `bundle install`
2. `rake db:migrate`
3. `rake db:seed`
4. `shotgun`

Then using a web client, navigate to the host printed out in the terminal, e.g. `http://127.0.0.1:9393/` or `http://127.0.0.1:9393/books`
