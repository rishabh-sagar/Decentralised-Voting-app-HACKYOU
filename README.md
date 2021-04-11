## Vote Chain - Decentralised Voting app
###  So what's the problem?
Democratic voting is a crucial and serious event in any country.The most common way in which a country votes is through a paper based system, but is it not time to bring voting into the 21st century of modern technology? Digital voting is the use of electronic devices, such as voting machines or an internet browser, to cast votes. These are sometimes referred to as e-voting when voting using a machine in a polling station, and i-voting when using a web browser. Security of digital voting is always the biggest concern when considering to implement a digital voting system. With such monumental decisions at stake, there can be no doubt about the system’s ability to secure data and defend against potential attacks. One way the security issues can be potentially solved is through the technology of blockchains.
## How we are solving it?
In the app the voter is first authenticate using a private key which will be unique to him after doing so the voter then has access to voting app where he will be displayed all the candidates then the voter can cast his vote. Once the author has casted his vote he won't be able to do so again which makes the process dummy votes proof also since each vote is store in distributed database the chances of external tempering is almost negligible .
## How to run the project
**Step 1: Installing Dependencies**

i) Node Package Manager(NPM)

You can see if you have node already installed by going to your terminal and typing:

    $ node -v

ii) Truffle Framework

It allows us to build decentralized applications on the Ethereum blockchain.

Install Truffle with NPM in your command line like this:

    $ npm install -g truffle

iii) Ganache

The next dependency is  [Ganache](http://truffleframework.com/ganache), a local in-memory blockchain. You can install Ganache by  [downloading it from the Truffle Framework website](http://truffleframework.com/ganache). It will give us 10 external accounts with addresses on our local Ethereum blockchain. Each account is preloaded with 100 fake ether.

iv) Metamask

The next dependency is the  [Metamask extension for Google Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en). In order to use the blockchain, we must connect to it. We will have to install a special browser extension in order to use the Ethereum block chain. That’s where metamask comes in. We’ll be able to connect to our local Ethereum blockchain with our personal account, and interact with our smart contract.

v) Now clone the repo by using
 `git clone https://github.com/rishabh-sagar/Decentralised-Voting-app-HACKYOU.git`
 
 **Step 2: Run the project**

 - Quick start the ganache
 - Now open terminal in the root of the cloned repo
 - Now run `$ truffle migrate --reset`
 - Now run `npm run dev`
 
  **Step 3: Configure metamask with ganache**
  Open Ganache and Click on any key(icon) to select the private key. 
  Copy this private key and now open metamask go to import account and paste this private key.
  
  **Step 4: Cast Your Vote**
    Now you can cast your vote and see the results as well

   
