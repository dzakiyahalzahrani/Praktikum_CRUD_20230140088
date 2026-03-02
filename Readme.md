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
   <img width="1600" height="879" alt="image" src="https://github.com/user-attachments/assets/3a6909cd-d326-4fd2-a897-a602993e8f04" />

2. update data
   <img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/be72802d-d2f6-4e60-8563-32fc0a9108ad" />

3. delete data
   <img width="1600" height="887" alt="image" src="https://github.com/user-attachments/assets/f1f04020-b898-45a7-bf7c-6dc18378f100" />
<img width="1600" height="886" alt="image" src="https://github.com/user-attachments/assets/b57294a3-c5bf-46e9-b6e0-ce326e745669" />

   
5. hasil tambah,delete,update
   <img width="960" height="531" alt="image" src="https://github.com/user-attachments/assets/efd571d6-fe50-4e75-a93a-f06935a1d381" />

   
