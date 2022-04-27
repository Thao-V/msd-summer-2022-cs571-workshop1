# CS571-Workshop-01: Bank Management App
## Rich MongoDB Documents Exercise
Please find below an Express application that connects to a local MongoDB instance, each document has the following structure for `banks` collection:
```JavaScript
{
    "_id":1,
    "name: "BOA",
    "branches": [
        {"_id":1, "name": "NY"},
        {"_id":2, "name": "IA"}
    ],
    "users":[
        {"_id":1, "name": "Michael", "accounts":[
            {"_id":1, "type": "debit", "number": 123, "routing": 123, "amount": 100},
        ]}
    ]
}
```
Your are responsible on writing code for 6 MongoDB queries within 6 pre-defined routes in `app.js` file:
1. Add a branch *(level 1)*
2. Update branch by ID *(level 1)*
3. Delete branch by ID *(level 1)*
4. Add a new account to a specific user *(level 2)*
5. Update an account's number *(level 2)*
6. Delete an account *(level 2)*
  
