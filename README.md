# Binary zkCircuit Demo
This is a simple implementation of a zkCircuit which is used to verify a simple binary circuit. This implementation uses circom programming language to implement the zkCircuit

### Setup
The setup is straight forward. follow the instructions given below to run and check the circuit
* Install the libraries using `npm i`
* Run `npx hardhat circom` to compile the circuit
* Run `npx hardhat run scripts/deploy.ts` to run the circuit

> note: If you are deploying the circuit to either mainnet or testnet, setup your private key in `.env` file based on `.env.example` in this repository



## DISCLAIMER
THIS PROJECT IS DONE AS A PART OF METACRAFTER'S ASSESMENT. DO NOT USE THIS IN PRODUCTION.