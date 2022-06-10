# mosfez-xen-synth

A microtonal-aware synth engine library for web.

**It's being built right now so it's probaby not finished and probably doesn't work or have fixed API or anything.**

## Development

This library is written in `typescript`, bundled with `rollup`, formatted with `prettier`, lined with `eslint` and tested with `jest`.

You will need `node@16` or greater and `yarn@1` installed globally. You'll also need `yalc` installed globally if you want to publish the library into the demo. Clone the repo and run `yarn prep` to install deps and build. There's also a demo site used to test the output of the library in `demo` which will be set up as part of `yarn prep`.

Then you can run:

- `yarn build` to build the `*.ts` source files into `*.js` files and `*.d.ts` type files in `/dist`.
- `yarn test` to run tests using `jest`.
- `yarn pretty` to run the auto-formatter `prettier`.
- `yarn lint` to run the linter `eslint`.

To simulate a publish / to update the `demo`, ensure you have `yalc` installed globally and then run `yarn update-demo`.
