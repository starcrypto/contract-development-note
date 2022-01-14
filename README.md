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

- solidity-upgrade:<br>
    Purpose: to upgrade old sol contracts.<br>
    Note: this tool is not released together with solc. You need to compile on your own
  - install: `git clone https://github.com/ethereum/solidity.git && mkdir -p solidity/build && cd solidity/build && cmake .. && make -j 8 && make install`
  - prepare: check `CMakeLists.txt` for the dependencies
  - source code: `slidity/toolssolidityUpgrade`
  - usage: check https://docs.soliditylang.org/en/develop/using-the-compiler.html#solidity-upgrade

Links:
------
- https://github.com/crytic/building-secure-contracts
- https://hackmd.io/@ChiHaoLu/HymtJS_oF sol contract note
