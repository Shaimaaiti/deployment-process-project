# Hosting a Full-Stack Application


### Front-End Application URL: http://udagramfront.s3-website-us-east-1.amazonaws.com/home
## About: 
Full-Stack application built for a retailer and deploy it to a cloud service provider so that it is available to customers. You will use the aws console to start and configure the services the application needs such as a database to store product information and a web server allowing the site to be discovered by potential customers.
## Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.
```
## Installation
```
Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
2. In AWS, provision a s3 bucket for hosting the uploaded files.
3. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
4. From the root of the repo, navigate udagram-api folder  `cd udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
5. Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
```
## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd udagram/udagram-frontend`
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

## Pipeline process
 ` .circleci/config.yml ` this file contains the process of Pipeline and contains 3 main points
1. orbs
2. jobs
3. workflows 
## License

[License](LICENSE.txt)
