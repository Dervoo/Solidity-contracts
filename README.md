# Solidity functions within Hardhat environment

This project demonstrates examples of Solidity contracts.

To deploy contract do those steps:

```shell
- npx hardhat compile
- npx hardhat run --network <your network> scripts/<name of the script file>.js
```
Database.sol:
```shell
Initiation of number and name of Person to the database. Storing all initiated informations and getting stored numbers with possibility of retrieving double number stored.
```
Donation.sol
```
Donation possibility to chosen account or owner of the contract. Also possibility to generate informations about amount of donations for both of them.
```
Emotions.sol
```
Possiblity to set emotion status of your choice from: Nothing, Love, Like, Hate and getting feedback which one has been chosen.
```
Inbox.sol
```
Setting two different messages and getting them on demand.
```
LibraryTerminal.sol
```
Adding people to the base by their names.
```
ShipmentStatus.sol
```
Getting shipment status from the contract: Pending/Shipped/Delivered.
```
Token.sol
```
Creation of ERC20 Token. Setting your own name, symbol, decimals and supply of the Token. Possible transfers and approval of transactions.
```
Guess.sol
```
Guess solvable be everyone with text reward. 
```
Puzzle.sol
```
Simple riddle with reward. Everytime you try to guess you have to pay 0.005 ether. Reward cumulates from entries and only one account will win and get all the money. After that no other account can win reward anymore.
```
UpgradedFile.sol
```
Upgradeable contracts with deployment script /scripts/UpgradedFile.js
```
* [Linkedin](https://www.linkedin.com/in/bartosz-osi%C5%84ski-8248a421b/)