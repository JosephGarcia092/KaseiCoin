# KasieCoin

After waiting for years and passing several tests, the Martian Aerospace Agency selected you to become part of the first human colony on Mars. As a prominent fintech professional, they chose me to lead a project developing a monetary system for the new **Mars colony**. You decided to base this new system on blockchain technology and to define a new _cryptocurrency_ named **KaseiCoin**. (Kasei means Mars in Japanese.)

I have created a _Crowdsale_ that is **ERC-20** compliant. (a blockchain representation of something that meets the standards set by the Ethereum community to be considered a smart contract standard-compliant token) To be able to exchange _Earth Money_ to _KaseiCoin_.


## Steps I took to complete 

- Create the KaseiCoin Token Contract
- Create the KaseiCoin Crowdsale Contract
- Create the KaseiCoin Deployer Contract
- Deploy and Test the Crowdsale on a Local Blockchain
- Optional Extension: Extend the Crowdsale Contract by Using OpenZeppelin


### KaseiCoin Creation (Contract)

Note that with Solidty there is a need for a _Pragma_ which sets a version for _Compilation_, this contract we are gonna use the _Pragma_ and set it to ^0.5.0.


After setting the pragma we have imports that are needing to be done so we can utilize _OpenZepplin_.

* REC20
* ERC20Detailed
* ERC20Mintable

I created (defined) a contract named _KaseiCoin_, and added a constructor with the parameters: _name, symbol,_ and _inital_supply_. The constructor tells the contract what is needed to have as inputs. As part of the _constructor_ of the _KaseiCoin_, I addded a call to the _constructor_ of _ERC20Detailed_ with passing the parameters **name, symbol, 18** 



## KaseiCoin Crowdsale creation(contract)
