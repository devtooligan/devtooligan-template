# devtooligan-template

# huff-project-template • [![ci](https://github.com/devtooligan/devtooligan-template/actions/workflows/ci.yml/badge.svg)](https://github.com/devtooligan/devtooligan-template/actions/workflows/ci.yml) ![license](https://img.shields.io/github/license/devtooligan/devtooligan-template.svg) ![solidity](https://img.shields.io/badge/solidity-^0.8.15-lightgrey)

Versatile Huff Project Template using Foundry.


## Getting Started

Click "Use this template" on [GitHub](https://github.com/huff-language/huff-project-template) to create a new repository with this repo as the initial state.

Once you've cloned and entered into your repository, you need to install the necessary dependencies. In order to do so, simply run:

```shell
forge install
```

To build and test your contracts, you can run:

```shell
forge build
forge test
```

For more information on how to use Foundry, check out the [Foundry Github Repository](https://github.com/foundry-rs/foundry/tree/master/forge) and the [foundry-huff library repository](https://github.com/huff-language/foundry-huff).


## Blueprint

```ml
lib
├─ forge-std — https://github.com/foundry-rs/forge-std
├─ foundry-huff — https://github.com/huff-language/foundry-huff
scripts
├─ Deploy.s.sol — Deployment Script
src
├─ SimpleStore — A Simple Storage Contract in Huff
test
└─ SimpleStore.t — SimpleStoreTests
```


## License

[The Unlicense](https://github.com/huff-language/huff-project-template/blob/master/LICENSE)


## Acknowledgements

- [forge-template](https://github.com/foundry-rs/forge-template)
- [devtooligan-template](https://github.com/devtooligan/devtooligan-template)


## Disclaimer

_These smart contracts are being provided as is. No guarantee, representation or warranty is being made, express or implied, as to the safety or correctness of the user interface or the smart contracts. They have not been audited and as such there can be no assurance they will work as intended, and users may experience delays, failures, errors, omissions, loss of transmitted information or loss of funds. The creators are not liable for any of the foregoing. Users should proceed with caution and use at their own risk._