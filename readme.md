# Welcome to the Anythink Market repo

To start the app use: `./start.sh`, it'll start both the backend and the frontend.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

### Dependencies

Install MongoDB:
`docker run --name mongo -p 27017:27017 -d mongo`

Set MongoDB connection string as an environment variable:
`export MONGODB_URI=mongodb://localhost:27017`

Install yarn:
`brew install yarn`

Install node modules with yarn:
`yarn install`

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
