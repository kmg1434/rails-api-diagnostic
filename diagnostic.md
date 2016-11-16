# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
To store data remotely and to abstract data from the user (only retrieve or
show specific relevent data to user) and to allow multiple network connections.
Something to do with security as well.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Rachel said something about us using views still but in a different way than the
"MVC" way. I dont know what it is though.
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destory
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Controllers
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
- index
- create
- show
- update
- destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
- Router chooses which controller to send request to
- Controller looks at Model
- model either accepts or rejects request and sends feedback back to controller
- controller passes info to client
```

What is the command to generate a new rails-api app?

```bash
bundle exec rails-api new my_api
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
bundle exec rake db:drop
bundle exec rake db:create
bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails g scaffold pet name:string age:integer
```
