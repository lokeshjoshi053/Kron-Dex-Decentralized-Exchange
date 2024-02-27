  <h1>Kron-dex</h1>

  <h4>
    <a href="https://projectkron.com/">Website</a>
    <span> | </span>
    <a href="https://discord.gg/HSeFXbqsUX">Discord</a>
    <span> | </span>
    <a href="https://github.com/project-kron/awesome-kron">Awesome</a>
    <span> | </span>
    <a href="https://dex.projectkron.com/#/">DEX</a>
    <span> | </span>
    <a href="https://github.com/project-kron/kron-ts">TypeScript</a>
  </h4>
</div>

## Program Deployments

| Program | Devnet | Mainnet Beta |
| --------|--------|------------- |
| [DEX](/dex)     | `DESVgJVGajEgKGXhb6XmqDHGz3VjdgP7rEVESBgxmroY` | `9xQeWvG816bUx9EPjHmaT23yvVM2ZWbrrpZb9PusVFin` |

## Note

* **kron is in active development so all APIs and protocols are subject to change.**
* **The code is unaudited. Use at your own risk.**

## Contributing

### Install Rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustup component add rustfmt
```

On Linux systems you may need to install additional dependencies. On Ubuntu,

```bash
sudo apt-get install -y pkg-config build-essential python3-pip jq
```

### Install Solana

Directions can be found [here](https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool).

### Download the source

```bash
git clone https://github.com/lokeshjoshi053/Kron-Dex-Decentralized-Exchange.git
```

### Build, deploy, and test programs

See individual crates for documentation. For example, to build the dex see its [README](https://github.com/lokeshjoshi053/Kron-Dex-Decentralized-Exchange/tree/master/dex).

## Running a local Solana cluster

The easiest way to run a local cluster is to use [solana-test-validator](https://docs.solana.com/developing/test-validator).

## Directories

* `assert-owner`: Solana utility program for checking account ownership.
* `common`: Common rust utilities.
* `dex`: kron DEX program and client utility.
* `pool`: kron pool protocol.
* `scripts`: Bash scripts for development.
