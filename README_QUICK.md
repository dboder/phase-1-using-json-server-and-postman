

```console
$ npm install -g json-server
```

```console
$ touch db.json
```

Open this file in your text editor and paste in the following content:

```json
{
  "articles": [
    {
      "id": 1,
      "title": "Example Article",
      "content": "This is an example."
    },
    {
      "id": 2,
      "title": "Second Article",
      "content": "This is also an example."
    }
  ]
}
```


```console
$ json-server --watch db.json
```
go to http://localhost:3000/

```json
[
  {
    "id": 1,
    "title": "Example Article",
    "content": "This is an example.",
  },
  {
    "id": 2,
    "title": "Second Article",
    "content": "This is also an example.",
  },
];
```

POSTMAN POST
Finally, before we can send our request, we need to provide the data we want to send. In Postman, just below the URL bar, click the Body tab, then choose the raw option, and select JSON from the drop-down menu.

