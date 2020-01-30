# Api-for-testing-purpose

Execute using `node app.js`

Open postman

- Choose POST method
- URL `localhost:4100/mysql/register/json`
- Body pass number of users to be registered and the fields required to register the user  
`
{
    "numberOfUser": 10,
    "fields": ["id", "firstName", "middleName", "lastName", "fullAddress", "password"],
    "api": "http://httpbin.org/post" 
}
`
