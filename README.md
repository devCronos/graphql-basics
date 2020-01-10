graphiql in-browser tool for writing, validating, and testing GraphQL queries.
<br>
schema - what properties each object has and how are they related
<br>
schema require('graphql')
<br>
server require('express-graphql'), require('./schema/schema-completed')
<br>
<br>
Root Query = entry point - allows to jump and land on a very specific node
<br>
    resolve function = reach and grab data
                     = can return a promise and it knows and waits it to resolve
                     = looks for it if it doesnt have that property
                     = represents the edges in the graph
<br>
    fields - uses arrow function to return an object. Closure - the function is defined but not executed. Avoids circular references errors
<br>
<br>
    json-server = very cool for develpment https://github.com/typicode/json-server
<br>
<br>

```
query findCompany{
  first:company(id: "1"){
    id,
    name,
    users{
      firstName,
      age
    }
  },
  alias:company(id: "2"){
    ... companyDetails
  }
}
 
fragment companyDetails on Company {
  id
  name
  description
}
```


<br>
<br>
## Mutations
<br>
PUT = complete replace data on the db
PATCH = updates sent fields
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>











