# Quest-Submission
Bootcamp Emerald Academy

# Chapter1 Day 1
1. Explain what the Blockchain is in your own words.
 
The blockchain is an open decentralized public database whitout midleman for the transaction.

2. Explain what a Smart Contract is.

A Smart Contract is a program with rules developed for the user to interact with.

3. Explain the difference between a script and a transaction.

A script allow you to view data on the blockchain, a transaction is the action to change data.

# Chapter1 Day 2
1. What are the 5 Cadence Programming Language Pillars?

safety, clarity, approachability, dev experience, ressource oriented programming

2.In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?

For the development and adoption of  flow cadence language must have all this perks.

# Chapter2 Day1
1.Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.



2.Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.

![JackobTucker](https://user-images.githubusercontent.com/79799749/188926959-1dfae10b-2e6d-498a-ad8a-acf82ec312d8.png)

![ScriptJT](https://user-images.githubusercontent.com/79799749/188927563-15e479c8-29c6-4a98-ac44-af30f04af228.png)

![The-best](https://user-images.githubusercontent.com/79799749/188893515-80b90e12-6246-4b64-81e3-f62b3ac9b13b.png)

# Chapter2 Day2

1.Explain why we wouldn't call changeGreeting in a script.

2.What does the AuthAccount mean in the prepare phase of the transaction?

3.What is the difference between the prepare phase and the execute phase in the transaction?

4.Add two new things inside your contract:

A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
Add a script that reads myNumber from the contract

Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.
