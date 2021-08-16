# bearer-auth

# basic-auth


# LAB - 07
---
### Deployment Test

###### Author: Ibrahem Alomari

* ##### [Actions](https://github.com/ibrahemomari/bearer-auth/actions)
* ##### [Pull Request]()
* ##### [Heroku](https://ibrahem-basic-api-server.herokuapp.com/)

---
###### Setup


### `.env`
 > PORT: 8000
NODE_ENV=test
DATABASE_URL=postgres://localhost:5432/lab7

---

###### Running the app:

* ####  `npm start` , `nodemon`

* #### Endpoint: */signin*
    * **Returns Object**

```javascript
{
    "username":"test",
    "password":"test"
}
```

* #### Endpoint: */signup*
* **Returns Object**

```javascript
{
    "username":"test",
    "password":"test",
    "token":"123456789abcd"
}
```

---

#### Tests
Unit Tests: `npm run test`
Lint Tests: `npm run lint`

---

#### UML

![](bearer.jpg);