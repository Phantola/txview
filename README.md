# txview

Txview is a cli-based tool for viewing transactions on the ethereum compatible blockchains using infura.

## Installation

```bash
brew tap phantola/tap
brew install txview
```

## Usage

1. Create a infura account for use infura api key. [Infura](https://infura.io/)

2. Make a file in `$HOME/.config/txview/config`
```bash
cd $HOME/.config/
mkdir txview && cd txview
touch config
```

3. Write your infura api key in config file.
```bash
your_infura_api_key
```

4. Run txview
```bash
txview eth-goerli 0x-tx-hash
``