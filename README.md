# Exercise Tracker

The Exercise Tracker project is one of the projects required to complete the freeCodeCamp Back-end Development and APIs certification


# Screenshots

![Screenshot_2023-11-26-13-39-29-827_com android chrome](https://github.com/freeCodeCamp/boilerplate-project-exercisetracker/assets/140446097/41ca35e3-c9b9-4f4f-9955-2d864fd6422c)


## Documentation

 - [MongoDB](https://www.mongodb.com/docs/)
 - [Mongoose](https://mongoosejs.com/docs/)
 - [Node.js](https://nodejs.org/en/docs)
 - [Express.js](https://expressjs.com/en/starter/installing.html)
 - [NPM](https://docs.npmjs.com/)


## Functionalities

- Create user
- Add exercises
- Find user with exercises


## Links

 - [Produção no Replit](https://replit.com/@muniquefeitoz4/boilerplate-project-exercisetracker?v=1)
 - [Sobre o projeto](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/exercise-tracker)
 - [Roadmap Back-end Development and APIs](https://www.freecodecamp.org/learn/apis-and-microservices)


## Responses exemples

- Exercise: 
```JSON
{
  username: "fcc_test",
  description: "test",
  duration: 60,
  date: "Mon Jan 01 1990",
  _id: "5fb5853f734231456ccb3b05"
}
```

- User:
```JSON
{
  username: "fcc_test",
  _id: "5fb5853f734231456ccb3b05"
}
```

- Log:
```JSON
{
  username: "fcc_test",
  count: 1,
  _id: "5fb5853f734231456ccb3b05",
  log: [{
    description: "test",
    duration: 60,
    date: "Mon Jan 01 1990",
  }]
}
```
