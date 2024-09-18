# Little Silk Road 

### Abstract:
This project aims to create service oriented architecture for an application. 

The backend exposes data through a set of API endpoints that communicate with a seperate front end application. The API handles CRUD operations and handles one-to-many relationships with SQL and ActiveRecord queries.

The frontend consumes data from the Rails API. Additionally, it enhances user experiance with a new interface to sort through sellers and their goods and services.

### Installation Instructions:

There are two halves to this application, a server and an interface.

**To install and run the server:**

1. Navigate to an empty directory
1. Fork and clone [this repository](https://github.com/stefanjbloom/little_silk_road)
1. `cd` into cloned repo
1. In a new terminal run `rails server`
  - Ensure the server is connected to port 3000

**To install this application to work with the server:**

1. Navigate to another empty directory
1. Fork and clone [this repository](https://github.com/jchirch/little-silkroad-fe)
1. `cd` into cloned repo
1. Run `npm install`
1. Run `npm run dev` to start developing.
1. Navigate to `http://localhost:5173/` in browser.

### Preview of App:
(Provide ONE gif or screenshot of your application - choose the "coolest" piece of functionality to show off. gifs preferred!)






----

### Context:
This project was completed over the course of an 8 day sprint by a team of Turing students.

### Learning Goals:
- Use ActiveRecord and SQL to write queries that deal with one-to-many database relationships
- Expose API endpoints to CRUD database resources
- Validate models and handle sad paths for invalid data input
- Test both happy and sad path functionality based on JSON contracts
- Use MVC to organize code effectively, lmiting data logic in controllers and serializers
- Track user stories with GitHub Projects
- Improve an existing FE application by:
  - Styling the user interface
  - Refactoring JavaScript code
  - Adding an additional FE feature
  - Practice individual research (articles, videos, mentors)



### Contributors:
Bloom, Stefan
  - [Github](https://github.com/stefanjbloom)
  - [LinkedIn](https://www.linkedin.com/in/stefanjbloom/)

Chirchirillo, Joe
  - [Github](https://github.com/jchirch)
  - [LinkedIn](https://www.linkedin.com/in/joechirchirillo/)

Fallenius, Karl
  - [Github](https://github.com/SmilodonP)
  - [LinkedIn](https://www.linkedin.com/in/karlfallenius/)

Messersmith, Renee
  - [Github](https://github.com/reneemes)
  - [LinkedIn](https://www.linkedin.com/in/reneemessersmith/)