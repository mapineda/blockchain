# Simple Python Blockchain

## Requirements

- flask
- requests
- IDE

## SetUp

1. `mkdir blockchain` # create folder
2. `mkvirtualenv blockchain --python=python` # create virtual env 
3. `pip install flask request` # install requirements

## Create

1. Create generator (branch lesson_001)
2. Add new transaction (branch lesson_002)
- After `new_transaction()` adds a transaction to the list, it returns the index of the block which the transaction will be added to—the next one to be mined. This will be useful to the user submitting the transaction.




### Example of a block

```
block = {
    'index': 1,
    'timestamp': 1506057125.900785,
    'transactions': [
        {
            'sender': "8527147fe1f5426f9dd545de4b27ee00",
            'recipient': "a77f5cdfa2934df3954a5c7c7da5df1f",
            'amount': 5,
        }
    ],
    'proof': 324984774000,
    'previous_hash': "2cf24dba5fb0a30e26e83b2ac5b9e29e1b161e5c1fa7425e73043362938b9824"
}
```
