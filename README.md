Smart Contract Development Notes
================================

Tools:
------
- solc-select<br>
    Purpose: to switch between different solidity versions
  - install: `pip3 install solc-select`
  - prepare: `solc-select install 0.8.10 && solc-select use 0.8.10`
  - switch to 0.7.6: `solc-select install 0.7.6 && solc-select use 0.7.6`
  - list installable versions: `solc-select versions`
  - installation path: `$HOME/.solc-select/`

