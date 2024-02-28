# Create token in Solidity

In these project we have to create a token which will have two paramaters values and address that will check total supply.

## Description

1.Firstly will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2.Then contract will have a mapping of addresses to balances (address => uint)
3.We will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount. 
4.Contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5.Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Installing

We are making these project on remix ethereum IDE.

### Executing program

  1. We are using remix ethreum ide for this project after completing the code. We have to compile and check.
  2. After that we have to deploy the contract we made.
  3. Then we will check the values are there or not.
  4. After this we will copy an address and paste it to mint and burn function and will check either it is giving correct values or not. 


## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Aryan



## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
