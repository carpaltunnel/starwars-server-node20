# This repo is no longer maintained and has been archived.

**NOTE** : This fork is still deprecated but updated so that it will actually run with Node.js v20.  This was done purely because the [GraphQL.org "learn" documentation](https://graphql.org/learn/queries/) references this data/implementation so it provides better examples for learning purposes.

You'll also need to install dependencies (as of 2024-11-02 with Node v20) using --legacy-peer-deps :
`npm install --legacy-peer-deps`

## Star Wars Example Server

This is a really simple GraphQL server that uses [Apollo Server](https://github.com/apollostack/apollo-server) and [GraphQL Tools](https://github.com/apollostack/graphql-tools) to serve the Star Wars example schema from http://www.graphql.org.

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/apollographql/starwars-server
cd starwars-server
# Because of the age of this project :
npm install --legacy-peer-deps
```

## Starting the server

```
npm start
```

The server will run on port 8080. You can change this by editing `server.js`.
