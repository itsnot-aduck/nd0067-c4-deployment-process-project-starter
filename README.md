# Udagram
 <strong><sup>Fullstack</sup></strong> [![CircleCI](https://circleci.com/gh/praveen-sripati/udagram-fullstack/tree/main.svg?style=shield)](https://circleci.com/gh/praveen-sripati/udagram-fullstack/tree/main)   <strong><sup>Frontend</sup></strong> [![CircleCI](https://circleci.com/gh/praveen-sripati/udagram-api/tree/main.svg?style=shield)](https://circleci.com/gh/praveen-sripati/udagram-api/tree/main)   <strong><sup>API</sup></strong> [![CircleCI](https://circleci.com/gh/praveen-sripati/udagram-frontend/tree/main.svg?style=shield)](https://circleci.com/gh/praveen-sripati/udagram-frontend/tree/main)

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

<img src="screenshots/application.png" alt="angular-logo"/>

**App hosted in this** http://elasticbeanstalk-us-east-1-489886612742.s3-website-us-east-1.amazonaws.com/
## Getting Started

1. Clone this repo locally into the location of your choice.
1. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
1. Open a terminal and navigate to the root of the repo
1. follow the instructions in the installation step
### Dependencies

```javascript
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.
```

### Installation

Provision the necessary AWS services needed for running the application:

1. In Local, provision a available database running Postgres.
1. Locally, you can specify environment variables in .env files. The required variables are listed down in `src/config/config.ts` in *udagram-api*.
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
1. Use `npm run build` for production build for both.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## Screenshots

### CircleCI Fullstack
<img src="public/image.png" alt="overall"/>
<img src="public/image2.png" alt="build"/>
<img src="public/image3.png" alt="deploy"/>

### S3
<img src="public/S3.png" alt="S3"/>

### Elastic Beanstalk
<img src="public/eb.png" alt="Elastic Beanstalk"/>

### RDS
<img src="public/RDS.png" alt="RDS"/>

## License

[License](LICENSE.txt)