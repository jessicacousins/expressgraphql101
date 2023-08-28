# Express GraphQL 101

`node index.js` to spring up port 4000

- navigate to localhost:4000/graphql to query

## GraphQL Query

```
query findContact($iid: Int!) {
  contact(id: $iid) {
    name
    email
    age
  }
  contacts {
    name
  }
}
```
