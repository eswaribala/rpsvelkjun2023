# Searching with regular expressions

```
GET /products/_search
{
  "query": {
    "regexp": {
      "tags.keyword": "Veg[a-zA-Z]+ble"
    }
  }
}
```

GET /products/_search
{
  "query": {
    "regexp": {
      "name.keyword": "B[a-zA-Z]+ - [a-zA-Z]+d"
    }
  }
}