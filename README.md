# Golang

Prototype Blockchain build with GO

### Simple Blockchain in Go

This is a simple implementation of a blockchain in Go. The code defines a Block struct, which contains an Index, Timestamp, BPM, Hash, and PrevHash. It also includes functions to calculate the hash of a block, generate a new block, and check the validity of a block.

The blockchain is implemented as a slice of Block structs, with the first block being the genesis block. The code defines two endpoints: one for retrieving the entire blockchain and another for adding a new block to the chain.

When a new block is added to the chain, it is validated and appended to the chain only if it is valid. If the block is invalid, it is rejected.

To run the code, make sure to install all dependencies by running go mod tidy, then start the server with go run main.go. The server will listen on the address specified in the .env file.

This implementation is meant to be simple and is not intended for production use. It serves as an introduction to the basic concepts of blockchain technology and demonstrates how a blockchain can be implemented in Go.

