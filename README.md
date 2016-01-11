# live-vote

A learning project focused on redux.

## Description

A distributed live-voting app using React on the client with a Node server. Uses redux for stores and socket.io for
client-server communication. Specs are written with mocha + chai. 

Users are presented with a series of binary choices and votes are sent to a server which controls the advancement of 
voting rounds until a winner is determined.

## Install

Within both the client and server directories:

```
npm install
```

## Usage

### Client

```
webpack-dev-server
```

### Server

```
npm start
```

## Tests

Within either the client or server directory:

```
npm test
```
