Run the following commands to see the problem:

`yarn install`
`yarn build`

The top level "meta" tsconfig.json defines client/src before core. Client has a reference to core so core should be built first.