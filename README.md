# Package Subscribo PsrHttpMessageTools

[![Build Status](https://travis-ci.org/Subscribo/psr-http-message-tools.svg)](https://travis-ci.org/Subscribo/psr-http-message-tools)

## providing following tools to be used with PSR-7 compliant classes:
- Request Factory
- Uri Factory
- Response Parser

## Important notes:

- This is a beta version.
- This is an auxiliary package with limited functionality

## Installing

Add dependency on this package to your composer.json:
```json
    "require": {
        "subscribo/psr-http-message-tools": "^0.3.0"
    }
```

## Usage

### Factory

```php
    $request = \Subscribo\PsrHttpMessageTools\Factories\RequestFactory::make($uri, $data);
```

### Parser

```php
    $data = \Subscribo\PsrHttpMessageTools\Parsers\ResponseParser::extractDataFromResponse($response);
```

## Contributing

For contribution guidelines see [CONTRIBUTING.md](CONTRIBUTING.md)

## License

Package Subscribo PsrHttpMessageTools is published under [MIT License](http://opensource.org/licenses/MIT)
