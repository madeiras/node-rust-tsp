rust-tsp
==========

Playing with rust on the travelling salesman problem and genetic algorithm.

# node-rest-tsp

Exposes the rust tsp lib via REST. All data is exchanged as JSON.

## Requirements

```
Rust - curl -sSf https://static.rust-lang.org/rustup.sh | sh
Node
```

## Install and run

```
cargo build && cd node-rest-tsp && npm i && node app.js
```

## Node dependencies

* <a href="http://chaijs.com/">chai</a>
* <a href="http://chaijs.com/plugins/chai-json-schema">chai json validator</a>
* <a href="https://www.npmjs.com/package/enum">enum</a>
* <a href="https://www.npmjs.com/package/ffi">ffi</a>
* <a href="https://www.npmjs.com/package/hal">hal</a>
* <a href="https://www.npmjs.com/package/istanbul">istanbul</a>
* <a href="http://mochajs.org/">mocha</a>
* <a href="https://www.npmjs.com/package/node-cache">node-cache</a>
* <a href="http://mcavage.me/node-restify/">restify</a>
* <a href="https://github.com/visionmedia/supertest">supertest</a>
* <a href="http://underscorejs.org/">underscore</a>
