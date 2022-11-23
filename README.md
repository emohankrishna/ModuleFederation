# Implementation of Micro frontends with Module Federation technique using webpack module bundler.



- `Shell` is the host application.
- `Core` is library
- `app1` standalone application which exposes `Widget` component.
- `app2` standalone application which exposes `Widget` component that requires
  `momentjs`.

# Running Demo

Run `npm run start`. This will build and serve both `Shell`, `Core`, `App1`, and `App2` on
ports `3000`, `3001`, `3002`, and `3003` respectively.

- [localhost:3001](http://localhost:3001/) (Shell)
- [localhost:3001](http://localhost:3001/) (Core)
- [localhost:3002](http://localhost:3002/) (STANDALONE REMOTE - App1)
- [localhost:3003](http://localhost:3003/) (STANDALONE REMOTE - App2)

# Contributor details
