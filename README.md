# Unit Test Solidity Contracts

## Installation
```
sudo apt install npm
npm install
npm audit fix
npm install --save-dev ethereum-waffle
npm install @openzeppelin/contracts -D
npm i chai -D
npm i mocha -D
```

## Compiling the tests
```
npx waffle
```
To compile using a custom configuration file run:
```
npx waffle config.json
```
## Running the tests
```
npx mocha
npm test
```