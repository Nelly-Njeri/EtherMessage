# SimpleMessaging Contract

## EtherMessage is a Solidity smart contract that allows users to create, read, update, and delete messages on the Ethereum blockchain.

## Contract Overview

## The contract consists of the following key components:
Message Struct: Defines a struct to represent a message with fields for ID, sender address, and content.
Message Storage: Utilizes an array to store messages and a mapping to track message ownership.
Functions: Provides functions for creating, reading, updating, and deleting messages, along with a function to retrieve the total number of messages.

## Contract Functions

1. createMessage: Creates a new message with the specified content.
2. readMessage: Retrieves the details of a message by its ID.
3. updateMessage: Updates the content of a message by its ID (accessible only by the message sender).
4. deleteMessage: Deletes a message by its ID (accessible only by the message sender).
5. getTotalMessages: Returns the total number of messages stored in the contract.

## Usage

To interact with the contract:

1. Deploy the contract on the Ethereum blockchain.
2. Use Ethereum wallets or smart contract interfaces to call the contract functions.

## License

This project is licensed under the [MIT License](LICENSE).
