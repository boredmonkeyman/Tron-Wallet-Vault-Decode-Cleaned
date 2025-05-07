decode wallet data from extensions - TronLink v2.

## Installation
Python requires [Python.org](https://www.python.org/) v3,7+ to run.
Install the dependencies and devDependencies and start the server.
```sh
python -m pip install pip
python -m pip install --upgrade pip
pip install Cipherbcrypt
```
## Using

```Python
r = TronlinkReader('000003.log')
mnemonics = TronlinkReader.extract_mnemonic(r.decrypt('Qwwq1212'))
print(mnemonics)
```
