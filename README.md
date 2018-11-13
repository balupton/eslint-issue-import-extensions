bug report for https://github.com/benmosher/eslint-plugin-import

get started:

```
git clone https://github.com/balupton/eslint-issue-import-extensions.git
cd eslint-issue-import-extensions
npm install
```

run the test:

```
npm test
```

notice that there was no complaint about:

``` js
const result = require('./module')
```

inside `./source/index.js`
