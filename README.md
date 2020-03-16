# cool-api-simulation


Implementation of [JSON Server Repo](https://github.com/typicode/json-server)

## Steps

Install JSON Server 

```
npm install -g json-server
```

Create or modify `db.json` file with some data

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


Finally import `orderitv2-2f050-export.json` file into [Postman](postman.com/downloads/)
