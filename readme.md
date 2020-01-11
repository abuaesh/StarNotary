# Building a Cryprostar Dapp on Etherem
This project is the second project in the Udacity blockchain developer nanodegree. The project creates an ERC-721 token (called Noosa, has the sybol NSA). The Noosa token is non-fungible; meaning that each Noosa token has a different name, ID, and other properties. The project allows Ethereum users to register, exchange, transfer and lookup Noosa tokens. 

# Versions
This project was built using Truffle version v5.1.1 and OpenZeppelin  version openzeppelin-solidity 2.1.2

The following tasks were done as a part of the project:
## Task 1
Modify the StarNotary version 2 contract code to achieve the following:
1. Add a name and a symbol for your starNotary tokens. Resource
2. Add a function lookUptokenIdToStarInfo, that looks up the stars using the Token ID, and then returns the name of the star.
3. Add a function called exchangeStars, so 2 users can exchange their star tokens...Do not worry about the price, just write code to exchange stars between users.
4. Write a function to Transfer a Star. The function should transfer a star from the address of the caller. The function should accept 2 arguments, the address to transfer the star to, and the token ID of the star.
## Task 2
Add supporting unit tests, to test the following:
1. The token name and token symbol are added properly.
2. 2 users can exchange their stars.
3. Stars Tokens can be transferred from one address to another.
## Task 3
1.  Deploy your Contract to Rinkeby
2. Edit the truffle.config file to add settings to deploy your contract to the Rinkeby Public Network.
## Helper Points:
1. Command used to deploy to Rinkeby truffle migrate --reset --network rinkeby
2. You will need to have your Metamask’s seed and Infura setup.
This was shown to you in detail in the lesson on Solidity, while creating ERC-20 tokens on Rinkeby.
## Task 4
Modify the front end of the DAPP to achieve the following:
1. Lookup a star by ID using tokenIdToStarInfo() (you will have to add code for this in your index.html and index.js files)
