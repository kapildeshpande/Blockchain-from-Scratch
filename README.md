# Blockchain-from-Scratch
Implemented Blockchain and all its main functionalities from scratch in python

The github repository contains a basic implementation of a blockchain and its client using Python. This blockchain has the following features:

   - Possibility of adding multiple nodes to the blockchain
   - Proof of Work (PoW)
   - Simple conflict resolution between nodes
   - Transactions with RSA encryption

The blockchain client has the following features:

   - Wallets generation using Public/Private key encryption (based on RSA algorithm)
   - Generation of transactions with RSA encryption

This github repository also contains 2 dashboards:

   - "Blockchain Frontend" for miners
   - "Blockchain Client" for users to generate wallets and send coins
    
To run this project:

   - Create new virtualenv
   - Install all requirements
    ```pip install -r requirements.txt```
   - Run app.py for Blockchain Frontend, blockchain_client.py for Blockchain Client
   - You can create different PEERS by specifying different ports
    ```python app.py -p 5001``` 

