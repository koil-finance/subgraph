# Koil Finance Subgraph

The graphql schema is still under heavy development and will likely have major breaking changes.

This repo tracks the subgraph definition.

## Setup

### Prerequisites

- Global Yarn Packages
    - truffle
    - graph-cli

## Subgraph

Clone the koil-finance subgraph

```
git clone git@github.com:koil-finance/subgraph.git
```

Update deployed contract address in subgraph.yaml to the ones listed as part of the deploy

Install dependencies

```
yarn
```

Generate the graph code

```
yarn codegen
```

Deploy

```
yarn deploy
```

Any updates can be made to this repo and re-running `yarn deploy` without needing to re-initialize the environment.