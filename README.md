# JS401 - Simple-API
This lab uses json-server to run a simple server and Swagger to document the REST functionality of the server.

## Links and Resources
[Github Repo](https://github.com/401-advanced-javascript-1/simple-api)
[Travis](https://www.travis-ci.com/401-advanced-javascript-1/simple-api)

## Documentation

# Modules
- swagger.json
- db.json

# Setup
- .env requirements
    - REACT_APP_API_SERVER=http://localhost:3000
- Running the app:
    - Start json-server (json-server --id _id --watch ./data/db.json)
    - Get categories/products (http get :3000/categories)
    - Post to categories/products (echo '{"category": "Electronics", "name": "Television", "display_name": "TV", "description": "Tool for watching shows" }' | http post :3000/categories)

## Tests
- N/A
## UML
- N/A