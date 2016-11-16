# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
"The backend provides us with additional functionality thats not typically available with just a front end such as allowing us to store the state of our application and allowing users to interact with each other via the app."
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
"The Model layer of the MVC pattern is used by the controller to fetch data."
```

Which layer in the MVC pattern communicates with the model?

```bash
"The Controller layer."
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
"We have been using JSON responses instead of views and then using jQuery to manipulate the DOM based on those responses."
```

What does C.R.U.D stand for?

```bash
"Create, Read, Update, Delete"
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
"We find C.R.U.D actions in the model layer of the MVC pattern."
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
"index, show, create, update, destroy"
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. The webserver looks at the routes file to determine which controller to send the request to.
2. The controller passes the request to the appropriate model.
3. The model communicates with the database to perform the GET and then passes that information back to the controller
4. The controller passes the information back to the webserver
5. The webserver formulates an HTTP response and sends it back to the client.
```

What is the command to generate a new rails-api app?

```bash
rails-api new my_api
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
- bundle exec rake db:drop
- bundle exec rake db:create
- bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails g scaffold pet name:string age:integer
```
