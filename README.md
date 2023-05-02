# SimpleVoting
A simple voting application implemented using a smart contract written in solidity

## Project Name: Simple Voting Application

### Description:
Develop a simple voting application using Ethereum smart contracts. The application should allow users to vote for their favorite candidate and display the results of the vote.

### Tools and Technologies:
- Solidity (programming language for Ethereum smart contracts)
- Remix (browser-based IDE for Solidity)
- MetaMask (browser extension for interacting with Ethereum network)
- Ganache (local blockchain network for testing)
- Web3.js (JavaScript library for interacting with Ethereum network from a web application)

### Steps:
1. Create a new Solidity file in Remix and define a contract called "SimpleVoting". The contract should have the following variables:
   - An array of candidates, each represented by a string.
   - A mapping of candidate names to vote counts.
   - A boolean flag indicating whether voting is open or closed.
2. Define a function called "vote" that allows users to vote for their favorite candidate. The function should take a string parameter representing the name of the candidate and increment the candidate's vote count in the mapping.
3. Define a function called "getVoteCount" that allows users to view the current vote count for a specific candidate. The function should take a string parameter representing the name of the candidate and return the corresponding vote count from the mapping.
4. Define a function called "closeVoting" that allows the contract owner to close the voting. The function should set the "votingOpen" flag to false.
5. Compile and deploy the contract to your local blockchain network using Ganache.
6. Create a simple web application using HTML, CSS, and JavaScript that interacts with the smart contract using Web3.js and MetaMask. The application should allow users to:
   - Connect their MetaMask wallet to the Ethereum network.
   - View the list of candidates.
   - Vote for their favorite candidate.
   - View the current vote count for each candidate.
   - Close the voting (if they are the contract owner).
7. Test the application by connecting to the local blockchain network and interacting with the smart contract using MetaMask.

This is a simple beginner project to get started with smart contract development using Ethereum. You can expand on this project by adding features like authentication, multiple voting rounds, and more. Good luck!
