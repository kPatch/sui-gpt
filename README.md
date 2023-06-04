![SuiGPT](./SuiGPTLogo.png)

SuiGPT is a ChatGPT plugin designed to help out exploring the Sui Blockchain.

- [Features](#features)
- [ToDo](#todo)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Next Steps](#next-steps)

## Features

- [x] Retrieve transactions from the Sui Blockchain using a transaction digest
- [x] Retrieve account balance from the Sui Blockchain
- [x] Explain, debug, and create test cases for Sui Move code

# ToDo

- [ ] Get Account information
- [ ] Execute transactions
- [ ] Execute move calls

# Requirements

- Yarn 1.22.19 or above

# Installation

- Download the GitHub repository:
```bash
$ git clone https://github.com/kPatch/sui-gpt
```

# Usage

- Install dependencies for the plugin
```bash
$ cd plugin
$ yarn install
```
- Run plugin project
```bash
$ yarn dev
```

- Run local Alt GPT project on another terminal window
```bash
$ cd frontend
$ yarn install
$ yarn start
```

# Usage

- Make sure to have the Alt GPT window open in a browser at `http://localhost:3010/chat` and have the plugin selected
- Type in `Please explain this transaction: {Insert transaction digest}`