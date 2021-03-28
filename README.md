# Dummy Backend (Javascript)

Based in https://github.com/rwieruch/node-express-postgresql-server

## Run local environment

- `npm install`
- `npm start`

## GET Routes (Examples)

- http://localhost:3000
  - /messages
  - /messages/1
  - /users
  - /users/1


## CUrl

- Create a message with:
  - `curl -X POST -H "Content-Type:application/json" http://localhost:3000/messages -d '{"text":"Hi again, World"}'`
- Delete a message with:
  - `curl -X DELETE -H "Content-Type:application/json" http://localhost:3000/messages/1`
