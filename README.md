## Unnati_Meta_Pro-Solidity

## Introduction 
Im Creating project for solidity Aka Metacrafters in which I've used solidity language to create a token  .

# Brief About Code 
I have created my own token named "Unn" abbreviated as "Chore". There is the record of its total supply. And if someone mints some "Chore" tokens then it will be added to the total supply of it. Also if someone burns those tokens, it will get subtracted from the total supply (Only if there is enough balance).

### Installing

* I just used the Online Remix IDE for implementation of  the solidity code.
* Then I created a file in this repository named U_token.sol for publishing that same code on GitHub.
* I have used remix.ide for execution of the code .

## Implementation of Code
* Create a new folder 
* If Remix is set to auto compile and run, the code will be automatically compiled and executed. Otherwise, manually compile and run the code by selecting the "Compile and Run" option from the left menu.
* After compiling, deploy the contract to get the account address for next steps.
* The contract gets deployed successfully.
* Initially, the account balance is zero.
* To mint tokens, click on the "Mint" button, paste the account address, enter the desired token quantity (e.g., 400), and click "Transact" to add tokens to the account.
* To check the balance, click on "Balances," paste the account address, and click "Call" to view the account balance.
* to check the totalsupply click on it.
* To burn tokens, click on "Burn", paste the account address, set the value to be burnt (e.g., 60), and click "Transact" to reduce tokens from the account.
* To check the balance again, press "Call" to obtain the latest balance (e.g., 400-60 = 340 tokens).
* These are all the steps followed in the contract.

## AUTHORS
Unnati Chore

## License
This project is licensed under the [MIT] License - see the LICENSE.md file for details
