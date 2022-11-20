# README

REF: https://www.tutorialspoint.com/graphql/index.htm

## Body request : http://localhost:3000/graphiql

Example

```
{
   test
   greeting
   students {
      id
      firstName
      lastName
   }
   studentById(id:"S1002") {
      id
      firstName
      lastName
   }
}
```

## Architecture

### GraphQL Server with Connected Database

![A-1](./images/architecture_1.jpg)

### GraphQL Server Integrating Existing Systems

![A-2](./images/architecture_2.jpg)

### Hybrid Approach

![A-3](./images/architecture_3.jpg)
