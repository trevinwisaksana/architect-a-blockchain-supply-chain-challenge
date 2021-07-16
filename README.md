# Architect A Blockchain Supply Chain - Part B
This is a programming challenge to architect a supply chain using Soldity and Web3 library for the Ethereum network. The goal is to build a tool to track an item from when it was first harvested, processed, packaged, sold to a distributor, shipped to a retailer and finaly, to when it is first bought by a consumer. It has a website as a frontend that interfaces with the smart contracts to mark items as its state changes.

## Instructions
To build and run this project locally run these commands in the terminal
1. `npm install`
2. `truffle develop`
3. `truffle migrate --reset`
4. `npm run dev`
5. Open the website on http://localhost:8080/

To run this project on Rinkeby
1. `npm install`
2. `npm run dev`
3. Open the website on http://localhost:8080/
4. Connect your Metamask to the website (Rinkeby network must be selected)
 
## Contract Address
0xb9D2db992432f2784F0835cc3CA6Ba4ecEF08200

## Transaction ID
0x7513083a1bff7beca25694c488072c8bcc8bc5d17474341afaed75ca3c9a336d

## UML Diagrams
All diagrams are in the UML folder
- activity_diagram.pdf
- sequence_diagram.pdf
- state_diagram.pdf
- class_diagram.pdf

## Libraries
No additional libraries were used.

## IPFS
IPFS is not used in this project although attempts were made to store the frontend on it. However, there were issues with getting it uploaded as the file seems missing as it gives a 504 error code.

## Node Version
16.0.0

## Web3 Version
1.2.1

## Truffle Version
5.3.9

## Solidity Compiler Version
0.8.0
