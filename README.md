### Registration
POST/users

//Body {
{
  "user": {
    "username": "vasiliy",
    "email": "vasy123@mail.ru",
    "password": "qwerty"
  }
}
// Result
{
    "user": {
        "username": "vasiliy",
        "email": "vasy123@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDk0M2Q5NmY4YmVlMWIwMDU1MTk2YiIsInVzZXJuYW1lIjoidmFzaWxpeSIsImV4cCI6MTY4MDM2NzA2NSwiaWF0IjoxNjc1MTgzMDY1fQ.92R_HsL6FVV14VgXyoP7WGyZMDguTsYAqG4KZth9zKc"
    }
}
### Authentication
POST/users/login

//Body {
    "user": {
        "email": "vasy123@mail.ru",
        "password": "qwerty"
    }
}
// Result
{
    "user": {
        "username": "vasiliy",
        "email": "vasy123@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDk0M2Q5NmY4YmVlMWIwMDU1MTk2YiIsInVzZXJuYW1lIjoidmFzaWxpeSIsImV4cCI6MTY4MDM2NzMwNywiaWF0IjoxNjc1MTgzMzA3fQ.fWFQ2v0fjmZ457_lqzJ3ofKKdwtK7cJvGCsbndzu2ls"
    }
}
### Get current users
GET/user

// Result 
{
    "user": {
        "username": "vasiliy",
        "email": "vasy123@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDk0M2Q5NmY4YmVlMWIwMDU1MTk2YiIsInVzZXJuYW1lIjoidmFzaWxpeSIsImV4cCI6MTY4MDM2NzU2NCwiaWF0IjoxNjc1MTgzNTY0fQ.Gekt5fRdUcOCzqdM022TfWUJbLk69UEyhCJfvTMDLho"
    }
}
