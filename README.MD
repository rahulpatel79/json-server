1) Install  - json-server

2) ----- > npm install json-server

3) ----->  Create a db.json

4) {
  "posts": [
    { "id": "1", "title": "a title", "views": 100 },
    { "id": "2", "title": "another title", "views": 200 }
  ],
  "comments": [
    { "id": "1", "text": "a comment about post 1", "postId": "1" },
    { "id": "2", "text": "another comment about post 1", "postId": "1" }
  ],
  "profile": {
    "name": "typicode"
  }
}

5) ----------- > npx json-server db.json

6) view terminal in multiple servers 
endpoints
Endpoints:

http://localhost:3000/posts
http://localhost:3000/comments
http://localhost:3000/profile



This project uses [json-server](https://github.com/typicode/json-server) to simulate a fake REST API for testing purposes.
