# Module 19 Homework Challenge

### Background

!["starter"](Images/19-4-challenge-image.png)

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go. KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

### Instructions

The steps for this challenge are broken out into the following sections:

* Import Ethereum Transaction Functions into the KryptoJobs2Go Application
* Sign and Execute a Payment Transaction
* Inspect the Transaction on Ganache

### Results

Firstly note the ganache at block 0 below before any transactions aswell as the mnemonic seed phrase used in our .env file at the top.

!["ganache"](Images/Ganache%20and%20Mnemonic%20Seed.png)

I chose to hire Ash because he had the best Krypto2Go rating of 5. I hired him for 7 hours at 0.33 eth per hour. This created a total payable wage of 2.31 eth. His ethereum address 0x2422858F9C4480c2724A309D58Ffd7Ac8bF65396

!["Ash"](Images/Transaction%20Sent%20to%20Ash.png)

We can see this resulted in 2.31 eth being taken out of our account ganache at block 1.

!["Account"](Images/Post%20Transaction%20account.png)

