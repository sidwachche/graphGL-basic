# graphGL-basic

Qeury expample:
```
query {
  user(id:"25"){
    id
    firstName
    age
  }
}
```
Mutation expample:
```
mutation{ 
  editUser(id: "25", firstName:"sid"){
    firstName
    age
  }

}
```
