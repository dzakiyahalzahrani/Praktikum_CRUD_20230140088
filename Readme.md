# User API Spesification

## Create User

Endpoint : POST /api/users

Request Body :

````json
{
"nama" : "dzaki",
"usia" : 22
}
````



Response Body (success) :

```json
{
"data": {
"id": "1a55ea7b-1e1b-4dd4-b2f1-8dd8fc9c8c42",
"name": "dzaki",
"usia": 22
}
}
```



Response Body (failed) :

````json
{
"error": "User not found"
}
````

##Delete User
Endpoint : DELETE /api/users/id

````json
{
"message": "User deleted successfully"
}
````

Response Body (failed) :
````json
{
"error": "User not found"
}
````

1. tambah data
   
2. update data
   
3. delete data
   
4. hasil tambah,delete,update
   