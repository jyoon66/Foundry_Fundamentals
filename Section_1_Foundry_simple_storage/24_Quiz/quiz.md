1. What essential configuration detail specifies the network address required for tools and applications to communicate with a running blockchain node?
    * RPC URL
2. Which component functions as an integrated, local blockchain node designed for development within Foundry?
    * Anvil
3. In the context of blockchain systems, what level of control does a private key typically grant?
    * Complete control over the associated account and its assets.
4. What cryptographic element is essential for verifying that a transaction was authorized by the owner of the sending account?
    * A digital signature generated using the sender's private key.
5. Which component of a transaction's data structure serves as a counter to ensure sequential processing and prevent duplication from a specific sender?
    * Nonce
6. When managing code in version control systems, like Git, what standard practice helps prevent the accidental exposure of files containing sensitive information?
    * Listing the sensitive files or patterns in a dedicated ignore file (e.g., 'gitignore')
7. If a private key controlling valuable digital assets is inadvertently exposed, what is the most critical and immediate action required?
    * Transfer all assets controlled by the compromised key to a new, secure account/key immediately
8. Why is passing secret keys or passwords directly as command-line arguments generally considered insecure?
    * The command and its arguments may be logged in the shell's history file.
9. When interacting with a deployed smart contract, which type of operation requires a private key signature and consumes network resources (gas)?
    * An operation that modifies the contract's stored data.
10. If interacting with a smart contract returns a value encoded as a long hexadecimal string (e.g., `0x000...01A4`), what step is often needed to interpret this value?
    * Converting the hexadecimal string to a different numerical base, such as decimal.
11. What is a primary advantage of deploying a smart contract to a public testnet compared to exclusively using a local development environment?
    * It allows testing under conditions that more closely mimic a live public blockchain.
12. After executing a deployment command for a smart contract to a public network, what is a common method to verify that the contract was successfully created on the blockchain?
    * Using a block explorer (like Etherscan) to check the status of the deployment transaction hash and look for the contract creation event.