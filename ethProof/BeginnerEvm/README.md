
## Public Variables
tokenName: A string variable that stores the name of the token.
tokenAbbrv: A string variable that stores the abbreviation of the token.
totalSupply: A uint variable that stores the total supply of the token.
## Mapping Variable
balances: A mapping variable that maps addresses to their respective token balances.
## Mint Function
mint(address _address, uint _amount): A function that takes two parameters, an address and a value. The function increases the total supply by the given amount and increases the balance of the sender address by that amount.
## Burn Function
burn(address _address, uint _amount): A function that takes two parameters, an address and a value. The function deducts the value from the total supply and from the balance of the sender. It also has a conditional to make sure the balance of the sender is greater than or equal to the amount that is supposed to be burned.
## Usage
To use this contract, you can deploy it to the Ethereum network using a tool like Remix or Hardhat. Once deployed, you can interact with the contract by calling the mint and burn functions with the appropriate parameters.
