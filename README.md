# deno_superstruct

Copied from [superstruct](https://github.com/ianstormtaylor/superstruct) src
directory. A few modifications were made to fix `TypeScript` problems. Mostly
just replacing any `value` it didn't like with `(value as any)` and running
`> deno fmt`. Refer to superstruct's
[readme](https://github.com/ianstormtaylor/superstruct#readme) for
documentation.
