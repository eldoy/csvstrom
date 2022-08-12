# CSVStrom

Streaming CSV to JSON converter. Works well for large files.

CLI is included.

### Install

```
# For use programmatically
npm i csvstrom

# Use from command line
npm i -g csvstrom
```

### Usage

Programmatically:
```js
const csvstrom = require('csvstrom')
await csvstrom('codes.csv', 'codes.json')
```

Command line usage:
```sh
csvstrom inputfile.csv [outputfile.json]
```

WTFPL Licensed. Enjoy!
