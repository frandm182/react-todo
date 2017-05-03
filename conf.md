Install json-server: npm i -g json-server
Create db.json
{
  "todos": [
    {
      "id": 1,
      "name": "Setup server",
      "isComplete": true
    },
    {
      "id": 2,
      "name": "Start server",
      "isComplete": true
    },
    {
      "id": 3,
      "name": "Connect to server",
      "isComplete": false
    },
    {
      "id": 4,
      "name": "Setup fecth",
      "isComplete": false
    }
  ]
}

Execute db.json
json-server -p 8080 --watch db.json
