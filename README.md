# nimiq_rpc_class

It is based on: https://gist.github.com/Deadlyelder/6a946bd666786a8986b5118802e909ea


Usage:

```
>>> from nimiq_rpc_class import *

>>> host.call('consensus')
'syncing'

>>> blockNum = host.call('blockNumber')
>>> print(blokNum)
175783

>>> balance = host.call('getBalance','YOUR ADDRESS')
>>> print(balance)
0

```
