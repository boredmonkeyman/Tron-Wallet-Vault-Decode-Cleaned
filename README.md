decode wallet data from extensions - TronLink v2.

## Installation
Python requires [Python.org](https://www.python.org/) v3,7+ to run.

```
Using

Python
r = TronlinkReader('000003.log')
mnemonics = TronlinkReader.extract_mnemonic(r.decrypt('Qwwq1212'))
print(mnemonics)
```
