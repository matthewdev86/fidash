# FiDash
Finance dashboard 
* Uses Yahoo's public APIs. 

# Features
* Search for any stock symbol to view historical data, summary, and news.
* Add and remove stock symbols to favorites.
* Stock data refreshes every 15 seconds in the background.
* Settings are saved to local storage.
* Fully responsive.

# Quick Start

```bash
$ git clone https://github.com/matthewdev86/fidash.git
$ cd fidash
$ npm install
$ npm install -g @angular/cli
$ ng serve
$ Navigate to http://localhost:4200/
```

# Configuration

Default application server configuration

```js
var PORT             = 4200;
var APP_BASE         = '/';
```

Configure at runtime

```bash
$ ng serve --host 0.0.0.0 --port 4201
```

# Running tests

```bash
# Development. Your app will be watched by karma
# on each change all your specs will be executed.
$ ng test

# code coverage (istanbul)
# auto-generated at the end of `npm test`
# view coverage report:
$ ng test -sr -cc
```

# License

The MIT License
