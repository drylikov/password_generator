# Password generator.

Password Generator

## Install

```
$ npm install @drylikov/password_generator --save
```

## Usage

```js
var generate = require("@drylikov/password_generator");

var pass = generate();

console.log(pass); // => "gllusviuarzrdopp" //string

var pass = generate({
    length: 20,
    numbers: true,
    uppercase: true,
});
console.log(pass); // => "ZpfgmfLdw1RQ3wYgGFro" //string

```


### Options


|            Name          |                  Type                       | Default Value |
|--------------------------|---------------------------------------------|---------------|
| length                   | Integer                                     |       16      |
| numbers                  | Boolean                                     |     false     |
| symbols                  | Boolean                                     |     false     |
| uppercase                | Boolean                                     |     false     |