## Modify from vanilla template to demonstrate more complex query type

```
$ curl -H "Content-Type: application/json" -d '{ "q": "foo" }' http://localhost:8000/queries.json
```

```
$ curl -H "Content-Type: application/json" \
-d '{
  "q": "foo"
  "items" : [ {"name": "i1", "score":1.0 }, {"name": "i2", "score": 2.0 }]
}' \
http://localhost:8000/queries.json
```
