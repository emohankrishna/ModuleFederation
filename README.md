# Dynamic Remote Vendor Sharing Example

This example demos a basic host application loading remote component and sharing vendor code dynamically between unknown remotes

- `Shell` is the host application.
- `Core` is library
- `app1` standalone application which exposes `Widget` component.
- `app2` standalone application which exposes `Widget` component that requires
  `momentjs`.

# Running Demo

Run `npm run start`. This will build and serve both `Shell`, `Core`, `app1`, and `app2` on
ports `3001`, `3002`, and `3003` respectively.

- [localhost:3001](http://localhost:3001/) (Shell)
- [localhost:3001](http://localhost:3001/) (Core)
- [localhost:3002](http://localhost:3002/) (STANDALONE REMOTE - App1)
- [localhost:3003](http://localhost:3003/) (STANDALONE REMOTE - App2)
  <img src="https://ssl.google-analytics.com/collect?v=1&t=event&ec=email&ea=open&t=event&tid=UA-120967034-1&z=1589682154&cid=ae045149-9d17-0367-bbb0-11c41d92b411&dt=ModuleFederationExamples&dp=/email/advanced-api/ModuleFederation">
