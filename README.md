# Spoke-assessment Server

## API Doc - https://spoke-assessment-karo.herokuapp.com/api/v1/docs/

## Environment Setup

The following needs to be available for the Application to run.

- nodejs 16
- VS code ESLint

## Getting the App Locally

1. Clone this repository with this command
```bash
git clone git@github.com:Okprime/spoke-assessment.git
```


2. Install dependencies with this command
```bash
npm install
```

3. Ensure you have the local .env file for configuration parameters

## With Docker

4. Use docker to setup / startup postgresDB using the command:

```bash
docker build -t spoke . && docker run -p 4500:3000 -t spoke
```
NB: The port "4500" varies depending on you but port "3000" is fixed and it is connected to docker

## Without Docker

5. Run the app in development environment using this command
```bash
npm run start:dev
```

## Running tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```
