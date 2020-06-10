# axios-formatter

Format axios response to a human-readable string.


## Install

```
yarn add axios-formatter
```


## Usage

```ts
import format from 'axios-formatter';

const s = format(r); // `r` is instance of AxiosResponse

console.log(s); // s is human-readable string
```
