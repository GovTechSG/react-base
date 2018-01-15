# [WIP] React Project Base

Get started with a fully extensible React.js application built from empirical best practices.

## What's Included?

### Server-side

- Express for the base-server
- Secure
- CORS-enabled
- CSP-enabled
- Prometheus metrics endpoint
- Health check endpoint
- Readiness check endpoint

### Tooling

- Babel for ES6-compatibility
- Webpack for bundling

### Testing framework

- Karma for running tests
- Mocha for the test framework
- Chai as the assertion library
- Sinon as the mocking library

## How Do I Use This?

### Via Yeoman Generator

Run:

```bash
npm install -g generator-react-base;
```

### Via Docker Image

Create a Dockerfile with the following contents:

```Dockerfile
FROM govtechsg/react-base:v16
COPY . /app
RUN yarn

```

