# cool-api-simulation


Implementation of [JSON Server Repo](https://github.com/typicode/json-server)

## Steps

Install JSON Server 

```
npm install -g json-server
```

Modify `db.json` file as needed

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```


Start JSON Server

```bash
json-server --watch db.json
```


Finally import `API Simulation.postman_collection.json` file into [Postman](postman.com/downloads/)

