# Spatie docs

[![Netlify Status](https://api.netlify.com/api/v1/badges/6294fcf1-042c-424b-9874-44d7a60da9b4/deploy-status)](https://app.netlify.com/sites/masterix21-docs/deploys)

This repository contains the Hugo configuration of the docs site. The application is automatically deployed to https://docs.spatie.be

## Installation

First ensure that Hugo is installed on your system.

```
brew install hugo
```

Node.js is also a requirement. You can download node.js from [nodejs.org](https://nodejs.org/en/).

Next, fetch the content from our package repositories. You only need to run this step once.

```
node fetch-content.js
```

Now the site can be built with Hugo. During development, you can have Hugo spin up a local webserver and watch for changes.

```
hugo server
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email freek@spatie.be instead of using the issue tracker.

## Credits

- [Sebastian De Deyne](https://github.com/sebastiandedeyne)
- [Rias Van der Veken](https://github.com/riasvdv)
- [All Contributors](../../contributors)

## About Spatie

Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
