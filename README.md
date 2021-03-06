# What’s the Deal with Testing?!
[http://marcysutton.github.io/whats-the-deal-with-testing/](http://marcysutton.github.io/whats-the-deal-with-testing/)

By [Marcy Sutton](http://marcysutton.com)<br>
Senior Front-End Engineer at [Deque Systems](http://deque.com)

- twitter: [@marcysutton](https://twitter.com/marcysutton)
- github: [@marcysutton](https://github.com/marcysutton)

## Presenting at:
* Smashing Conf Barcelona

## Installation

Should you want to run this presentation from source for some reason, the **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Building from source locally
Some reveal.js features require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

1. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

1. Clone the reveal.js repository
```
$ git clone git@github.com:marcysutton/whats-the-deal-with-testing.js.git
```

1. Navigate to the reveal.js folder
```
$ cd reveal.js
```

1. Install local dependencies
```
$ npm install
```

1. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

1. <http://localhost:8000> opens dynamically

You can change the port by using `grunt serve --port 8001`.
