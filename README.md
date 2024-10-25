# Finternet with Formance Monorepo

This repository contains multiple submodules that represent different parts of the Finternet-inspired infrastructure. It includes components from the following repositories, which are forked from [Formance](https://github.com/formancehq) and tweaked for Finternet on Solana, with everything being on-chain:

- [`ledger`](https://github.com/finternet-by-terry/ledger): A high-performance, scalable ledger to support asset tokenization.
- [`payment`](https://github.com/finternet-by-terry/payment): Manages payment workflows and payment processing systems.
- [`stack`](https://github.com/finternet-by-terry/stack): The overall architecture stack that brings together different components for financial services.
- [`numscript`](https://github.com/finternet-by-terry/numscript): A language for scripting and automating asset transactions.

> **Note**: This project is a fork of Formance and is currently a work in progress. The fork has been adapted to fit within the Finternet framework on Solana, ensuring that all components operate on-chain.

## Structure

This monorepo contains the following directories for the submodules:
- `/ledger` - The ledger component.
- `/payment` - The payment processing system.
- `/stack` - The architecture stack for managing components.
- `/numscript` - The Numscript language for scripting asset transactions.

Each directory holds the corresponding repository's code and is synchronized as a submodule.

## Setup

To clone this repository along with the submodules, use the following command:

```bash
git clone --recursive https://github.com/finternet-by-terry/monorepo.git
```

If you have already cloned the repository but the submodules are not initialized, you can run:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To update submodules to their latest version, you can run:

```bash
git submodule update --remote --merge
```

## Contributing

For contributions to the individual components, please navigate to the specific repositories:
- [Ledger](https://github.com/finternet-by-terry/ledger)
- [Payment](https://github.com/finternet-by-terry/payment)
- [Stack](https://github.com/finternet-by-terry/stack)
- [Numscript](https://github.com/finternet-by-terry/numscript)

## License

This project is licensed under the MIT License. Please refer to the individual repositories for the full license text:
- [Ledger](https://github.com/finternet-by-terry/ledger)
- [Payment](https://github.com/finternet-by-terry/payment)
- [Stack](https://github.com/finternet-by-terry/stack)
- [Numscript](https://github.com/finternet-by-terry/numscript)

