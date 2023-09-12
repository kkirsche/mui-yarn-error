# `@mui/lab` installation issue

## Reproduction

To reproduce the error as of Tuesday, September 12, 2023, run `yarn add @mui/lab`:

## Example Output

The following was produced at 10:51 AM Eastern Time on Tuesday, September 12, 2023

```
❯ yarn add @mui/lab
➤ YN0000: ┌ Resolution step
➤ YN0001: │ Error: @mui/x-tree-view@https://pkg.csb.dev/mui/mui-x/commit/1f23b33d/@mui/x-tree-view isn't supported by any available resolver
    at kf.getResolverByDescriptor (/Users/kkirsche/.cache/node/corepack/yarn/3.6.3/yarn.js:391:1647)
    at kf.bindDescriptor (/Users/kkirsche/.cache/node/corepack/yarn/3.6.3/yarn.js:391:1036)
    at _ (/Users/kkirsche/.cache/node/corepack/yarn/3.6.3/yarn.js:439:7240)
    at async Promise.allSettled (index 0)
    at async io (/Users/kkirsche/.cache/node/corepack/yarn/3.6.3/yarn.js:390:10398)
➤ YN0000: └ Completed
➤ YN0000: Failed with errors in 0s 33ms
```
