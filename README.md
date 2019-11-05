# Directory Mock Services

_A Microservice API utilizing Node JS and Express._

_What_: 

## Prerequisites

### NPS

Flight Plans API uses [nps] to define and execute npm scripts without the cost of a bloated package.json and the limits of JSON.

`npm start` is defined (in `package.json`) as an alias for `nps`, hence all scripts are run via `npm start <...>`

## Setup

Clone this repo

```sh
git clone https://github.dx.utc.com/utdx/collins-ims-flight-plans-api
cd collins-ims-flight-plans-api
```

Install all dependencies

```sh
npm install
```

Run api in a terminal window:

```sh
npm start
```

Run integration tests in a terminal window:

```sh
npm start test
```

## Contributing

See [Contributing.md](CONTRIBUTING.md)

## Architecture Design Record

See [ADR.md](ADR.md)

[nps]: https://github.com/kentcdodds/nps
[confluence]: https://confluence.dx.utc.com/display/CIM/Collins+IMS+Marketplace
