# swc-return-repro

## Reproduction Steps

1. `yarn swc .\index.ts -o index.js`
2. `node index.js`

**Expected behavior:** It prints "test returned: 0"

**Actual behavior:** It prints "test returned: undefined"
