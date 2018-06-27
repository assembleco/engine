# Assemble Engine

In order to populate the application with relevant data,
you need to start up the Rails backend:

```bash
$ cd server
$ gem install bundler
$ bundle install
$ rails s
```

Test that the server is working with the command:

```bash
$ curl -X POST http://localhost:3000/evaluate -H "Content-Type: application/json" -d '{ "code": "2 + 2" }'
```
