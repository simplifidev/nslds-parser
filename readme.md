# nslds-parser
This module parses data obtained from the National Student Loan Data System found at https://www.nslds.ed.gov/nslds_SA/.

[![NPM](https://nodei.co/npm/nslds-parser.png)](https://nodei.co/npm/nslds-parser/)

# JavaScript Usage

```bash
npm install nslds-parser
```

```js
var NSLDSParser = require('nslds-parser')

var parser = new NSLDSParser({
  format: 'csv'
})

var stream = parser.parseFile(filename)
var stream = parser.parseStream(process.stdin)
```
