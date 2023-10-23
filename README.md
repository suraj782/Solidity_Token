## Solidity_Token

# Introduction
I'm developing a project for stability. Also known as Metacrafters, in which I created a token using the solidity language.

# Overview
I have created my own token named "Sur" abbreviated as "Ban". There is the record of its total supply. And if someone mints some "Ban" tokens then it will be added to the total supply of it. Also if someone burns those tokens, it will get subtracted from the total supply (Only if there is enough balance).

## Setting up

* To implement the solidity code, I only used the Online Remix IDE. Then, in order to publish the same code on GitHub, I created a file called Sur.sol in this repository.

## Executing program:

* For the code execution, I used remix.ide.

## Operational Functionality

Here are the steps;

* Start by creating a folder.
* If the Remix tool is set to compile and run your code it will do automatically. Otherwise you can manually select the "Compile and Run" option, from the menu.
* Once the compilation is successful deploy the contract to obtain the account address for steps.
*  You will see a confirmation that the deployment process has been completed successfully.
*  Initially the account balance will be set to zero.
* To mint tokens click on the "Mint" button. Then paste in your account address. Enter the desired quantity of tokens (900). Click "Transact" to add them to your account.
* To check your balance click on "Balances " paste your account address. Click "Call" to view your balance.
* If you need to check the supply of tokens there should be an option for that purpose.
* To burn tokens from your account click on "Burn " paste in your account address specify how tokens you want to burn (500) and click "Transact" to reduce them from your account.
* After burning tokens reassess your balance by pressing "Call" to get an updated balance (e.g. if you burned 500 tokens from a 900 token balance you should now have 400 tokens remaining).
*  These steps cover all functionalities within this contract.

## AUTHORS
Suraj Bankar

## License
This project is licensed under the [MIT] License - see the LICENSE.md file for details


