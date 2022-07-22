# ibc-tests-ics20

Simple repo showing how to use ts-relayer as a library to test cw20-ics20 contract

## Setup

Ensure you have node 14+ (16+ recommended):

```
node --version
```

Then install via npm as typical:

```
npm install
```

## Development

Build the source:

```
npm run build
```

Clean it up with prettier and eslint:

```
npm run fix
```

## Testing

This actually runs the test codes on contracts. To do so, we need to start two blockchains
in the background and then run the process:

**TODO**