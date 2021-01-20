# json-server-api
JSON server API for testing purposes

## Routes
### For REST:

- GET https://mockend.com/ignacio-badiola/json-server-api/posts
- GET https://mockend.com/ignacio-badiola/json-server-api/posts/:id
- GET https://mockend.com/ignacio-badiola/json-server-api/comments
- GET https://mockend.com/ignacio-badiola/json-server-api/comments/:id

### For GraphQL:
- https://mockend.com/org/repo/graphql
  
## Queries

### For REST:

Using query parameters to filter, sort and paginate lists:

- _eq: equal 
- _ne not equal
- _gt greater than
- _lt lower than
- _order: sort data (values: asc | desc)
- limit offset: use them to paginate your results

Examples: 
```js
GET /posts?date_order=desc
```

```js
GET /posts
    ?views_gt=10
    &published_eq=true
    &views_order=desc
    &limit=5
```

### For GraphQL:
Documentation can be found under:
- https://mockend.com/ignacio-badiola/json-server-api/graphql
