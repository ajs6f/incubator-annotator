# [Apache Annotator](http://annotator.apache.org/) (incubating)

> Apache Annotator provides annotation enabling code for browsers, servers,
> and humans.

* [`dev@` Mailing List archive](http://mail-archives.apache.org/mod_mbox/incubator-annotator-dev/)
* [Issue Tracker](https://issues.apache.org/jira/browse/ANNO)
* [Wiki](https://cwiki.apache.org/confluence/display/ANNO)

## Usage

We're currently pre-releasing development copies of each library that makes up
the sum total of Apache Annotator's code. You can grab any of them from our
[npm organization](https://www.npmjs.com/org/annotator).

```sh
$ # for example...
$ npm install --save @annotator/dom
```

##### Requirements

- [node](https://nodejs.org) >= 8.x
- [yarn](https://www.yarnpkg.com/) >= 1.5.1


## Development

##### Requirements

We use [Lerna](https://lernajs.io/) to juggle the various Apache Annotator
libraries. If you'd like to contribute, you'll need the following:

- [node](https://nodejs.org) >= 8.x
- [yarn](https://www.yarnpkg.com/) >= 1.5.1

##### Setup

```sh
$ yarn install
```

##### Test

```sh
$ yarn test
```

##### Run localhost demo server

```sh
$ yarn start
```

Once the test server has started, you can browse a local demo, and run tests in
a browser by visiting `http://localhost:8080/`.


## Web Annotation Data Model Validation

If you have any Web Annotation Data Model JSON documents, you can validate them
using the `validate` script:


```sh
$ yarn validate --url ../anno1.json
```


# License

Apache License 2.0
