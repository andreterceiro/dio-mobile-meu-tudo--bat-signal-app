# General 

Please see [this file](briefing.pdf) to see the challenge.


# Project location

The project is located in the directory bat-signal-app


# Initial code of the Project

The initial code of the project was developed with this command:

```
npx create-expo-app bat-signal-app -t
```


# JSON server

This app comes with a very simple REST server to receive and provide contact data.

Before starting the JSON server (name of the package that provides the API), please install the Node.JS dependencies with the command:

```sh
npm install
```

Then start the API with the command:

```sh
json-server --watch db.json
```

Documenting the more basic endpoints:

- **GET http://127.0.0.1/contatos**: list all the contacts in the database;
- **POST http://127.0.0.1/contatos**: add a contact.