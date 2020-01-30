# Api-for-testing-purpose

Clone the project on your local environment

install npm packages required using `npm i`

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
