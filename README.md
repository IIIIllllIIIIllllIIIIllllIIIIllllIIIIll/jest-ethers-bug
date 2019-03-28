## Building

```
yarn
```

## What's The Bug:

Compare these two benchmarks:

```
node -e 'require("./timing.js")();'
```

```
yarn run jest
```

the later is much slower