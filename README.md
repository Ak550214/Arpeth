# Arpeth
# ARPCOIN (Creating Token)

Several different token features are going to be implemented with the help of this Solidity contract. In the course of this procedure, we will acquire the knowledge necessary to generate a token, mint fresh tokens, and deploy them. Aside from that, I was able to learn how to manufacture new tokens and burn old ones.

## Description
ARPCOIN is smart contract developed for creation and maintenance of new token on blockchain. It has many capabilities like as producing a token, minting new token, burning current tokens and tracking token balances of addresses. It assists in deployment of tokens with data like initial supply,token name and abbrevation for the token . ARPCOIN provides a simple and versatile method for token generation, ideal for many decentralized applications.

## Getting Started
### Installing
To utilise Arpcoin , simply download or clone the solidity contact file connected to this repository.

### Executing program
To execute this application, you may utilise Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/. Further steps,

1.Compile the ARPCOIN contract on an Ethereum-compatible network.

2.Deploy the ARPCOIN contract on an Ethereum compliant network.

3.Now an account address is formed for that token copy it and paste it into mint token together with appropriate amount of tokens to be manufactured.

4.You can also check the balance of token in balance by putt in the account address into it.

5.For burning the tokens input the account address and no. of token needs to be burnt then click on transact.

These are procedures by which we may mint tokens, burn tokens and tracking token balance of addresses.

code blocks for commands
```
 // mint function
  function mint(address ADD,uint value) public{
    totalSupply += value ;
    balances[ADD] += value;
  }

// burn function
  function burn(address ADD,uint value) public{
    if(balances[ADD] >= value) {
      totalSupply -= value ;
      balances[ADD]-= value;
   }
}
```

## Help
For better understanding we have learn the concept of solidity

## Authors

 Arpan Kumar 
 [@ironextreme5@gmail.com)


## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
