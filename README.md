Before start make sure that Docker is running on your machine.
For set up db run this command: yarn db:dev:up && yarn db:dev:migrate
Then you can run the app using command: yarn start:dev.

To run the e2e tests, firstly set up test env with this commands:
yarn db:test:up && yarn prisma:test:deploy

And then you can run e2e tests: yarn test:e2e
