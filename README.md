
primeupto is an math library for JavaScript and Node.js. It help you to find all prime number.

[![Version](https://img.shields.io/npm/v/primeupto)](https://www.npmjs.com/package/primeupto)
[![license](https://img.shields.io/npm/l/primeupto)](https://www.npmjs.com/package/primeupto)
[![download](https://img.shields.io/npm/dw/primeupto)](https://www.npmjs.com/package/primeupto)
[![download](https://img.shields.io/npm/dt/primeupto)](https://www.npmjs.com/package/primeupto)
[![Fork](https://img.shields.io/github/forks/letskhabar/primeupto?label=fork&style=social)](https://github.com/letskhabar/primeupto/fork)
[![Star](https://img.shields.io/github/stars/letskhabar/primeupto?style=social)](https://github.com/letskhabar/primeupto/stargazers)
[![watch](https://img.shields.io/github/watchers/letskhabar/primeupto?style=social)](https://github.com/letskhabar/primeupto/watchers)


## Features

- find all prime number upto n.
- find all prime number from m to n.  // comming soon
- find number of prime upto n.
- find number of prime from m to n.
- Can be used in command line as well.
- Runs on any JavaScript engine.
- Is easily extensible.
- Open source.

## Usage

primeupto can be used in both node.js and in the browser.

Install primeupto using [npm](https://www.npmjs.com/package/primeupto):

    npm install primeupto


```js
const {primeupto,primelength} = require('primeupto');

console.log(primeupto(5));   // 2,3,5
console.log(primelength(5));   // 3
console.log(primeupto(34));  // 2,3,5,7,11,13,17,19,23,29,31
console.log(primelength(34));  // 11
console.log(primeupto(25));  // 2,3,5,7,11,13,17,19,23
console.log(primelength(25));  // 9
console.log(primeupto(53));  // 2,3,5,7,11,13,17,19,23,29,31,37,41,43,47,53
console.log(primelength(53));  // 16

```

## Run

```
npm test
```

See the [Getting Started](https://github.com/letskhabar/primeupto) for a more detailed tutorial.


## Documentation

- [Getting Started](https://github.com/letskhabar/primeupto)
- [Examples](#)
- [Overview](https://github.com/letskhabar/primeupto)
- [History](#)



Clone the project from github:

    git clone https://github.com/letskhabar/primeupto.git
    cd primeupto





## License
MIT,  Copyright (C) 2020