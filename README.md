# Fake_Product_Identification
This project is to identify that buyer is buying original product through QR scanner using Blockchain Technology.

# Project Description:
As we all know every product have there fake brand out there.  Each well known brand has counterfeit makers selling similar thing at less expensive rates by compromising with the real quality. Indeed, even the specialists of the first organization will most likely be unable to recognize counterfeit items and their genuine items.We influence the possibility of Bitcoin's blockchain that anybody can really look at the confirmation of ownership of equilibrium. Alongside this, we intend to utilize QR codes. We intend to carry out a proof-of-idea framework utilizing a blockchain-based decentralized application which provides a client with the whole history of an item (eg - brand data, owner, and so on).

# Problem Statement:
Nowadays, when the supply of ingenuine products is becoming a common issue. How can the buyer recognize whether the brand and product is trustworthy or not? This affects the companies name, sales, and profit of the companies. Blockchain technology is used to identification of real products and detects fake products.

# Solution Statement:
Blockchain Technology is utilized to distinguishing proof of genuine items and identifies counterfeit items. In this Project, with arising patterns in versatile and remote innovation, Quick Response (QR) codes give a vigorous strategy to battle the act of duplicating the items. fake items are recognized utilizing a QR code scanner, where a QR code of the item is connected to a Blockchain. Thus, this framework might be utilized to store product details and created unique code of that item as blocks in the database. It gathers the unique code from the client and compares the code against entries in the Blockchain database. If the code matches, it will give a notice to the client, if not it will give the warning to the client that the item is fake.

# System Architecture:
<img width="848" alt="image" src="https://user-images.githubusercontent.com/99914023/185422978-87b94952-8f0e-485f-8824-cd273d71ec3d.png">

# Benefits:
- By using Blockchain Technology, Customers or users does not depends upon third party users for confirmation for product authenticity and safety.
- Prevents the loss in sales.
- Not only limited to particular business can be used in many supply chain businesses.
- Provides a secure and trusted tracking system from one end to another end.

# Built With:

 ### _Mobile App:_

-	Android Studio - Android app
-	NodeJS - Server Environment
-	MySQL - Database

 ### _Blockchain:_

-	Ethereum - Blockchain Network
-	Solidity - Smart Contracts
-	Ganache - Create private Ethereum blockchain to run tests

 ### _Website:_

-	HTML - Markup language for creating web pages
-	CSS - Style Sheet Language
-	JavaScript - Scripting Language for web pages
-	Bootstrap - Templating

# Restrictions:
- The customer or user needs to have a QR code scanner in order to check the product information.
- Products that have already been manufactured prior to the day this application has been established cannot be tracked.
- At the moment, we are dependent on the company to register with our services, without which, we cannot provide information about a brand to the user.

# Conclusion:
To conclude, Counterfiet products are developing these days dramatically with huge number. Thus, there is strong need to identify fake products and blockchain technology is utilized to recognize counterfeit products. Besides, the data is encoded into a QR code. Customers or clients scan the QR code and afterward they can recognize the duplicate product. Digital information of products can be put away as blocks in blockchain technology.  Hence, the proposed framework is valuable for the customer to identify counterfeit items in the supply chain. Customers can scan QR codes assigned to a product and can get all the data like transaction history, current owner based on which end-user can check regardless of whether the product is certifiable or not.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## _Prerequisites_
What things you need to install the software and how to install them Installing NodeJs

```
$ sudo apt-get install nodejs
```

Installing [Android Studio](https://developer.android.com/studio/)

# Installing
A step by step series of examples that tell you how to get a development env running

Cloning the repo

```
$ git clone https://github.com/kylelobo/AuthentiFi.git
```

Installing the dependencies

```
$ cd AuthentiFi
$ npm install
```

Running the server

```
$ node server.js
```

# Deployment

### 1. Instantiate your data directory

```
geth --datadir ./myDataDir init ./myGenesis.json
```

### 2. Start your Ethereum peer node.

Networkid helps ensure the privacy of your network. You can use any number here (where we used “1114”), but other peers joining your network must use the same one.

```
geth --datadir ./myDataDir --networkid 1114 console 2>> myEth.log
```
