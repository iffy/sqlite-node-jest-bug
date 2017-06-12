Steps to duplicate error:

1. `yarn`

2. `yarn test`

Error:

```
yarn test v0.24.6
$ jest -c src/__tests__/jestconfig.json 
 FAIL  src/__tests__/test_foo.js
  ● Test suite failed to run

    Cannot find module '../package' from 'node-pre-gyp.js'
      
      at Resolver.resolveModule (node_modules/jest-resolve/build/index.js:179:17)
      at Object.<anonymous> (node_modules/sqlite3/node_modules/node-pre-gyp/lib/node-pre-gyp.js:60:17)

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        0.618s
Ran all test suites.
```

I'm running macOS 10.12.4
