# React Exercise

React app bootstrapped from [Create React App](https://github.com/facebookincubator/create-react-app).

Setup it with Yarn:

```
$ yarn
```

Then start the server like:

```
$ npm start
```

## Lugg Request Flow

The goal of this exercise is to implement as much as possible of the flow to request a Lugg on the web:

- [Prototype](https://framer.cloud/LYpgZ)
- [Design](https://s3-us-west-1.amazonaws.com/lugg-exercises/lugg-request-flow.png)

It starts once we have the origin and destination addresses from the user (for example, entered in our home page to get a fare estimate). With these in hand we'd forward the user to this React app, kicking off the flow to book a Lugg.

Feel free to stub everything that will be needed in this flow in whatever way you prefer:

- The origin and destination addresses
- The availability schedule
- The API calls to verify a number, apply a code and book the Lugg

We recommend focusing on the React foundation first, and then styling it as time allows.
