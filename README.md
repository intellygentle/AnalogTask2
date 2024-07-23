# AnalogTask2
This repo is for Analog watch portal tasks

## if you haven't registered https://testnet.analog.one/#/?signup&referral=4IENHO
# Understanding the Interface 
## this is the testnet page and these are the task we'll complete
![1000005974](https://github.com/user-attachments/assets/747b3fb5-a3d9-4bc6-860c-948e87ae0ac3)
## this is the watch page.
![1000005976](https://github.com/user-attachments/assets/d354deec-90d5-4b62-a236-c922556bbf0a)
## at the library we'll see deployed smart contracts and deployed views 
## at the view builder we'll deploy our view
## at the smart contract we'll list our smart contract 
## at the profile you can copy your "an" addy and request faucet on discord then deposit to the analog page

# Listing a Smartcontract
## use your smart contract you deployed for the gmp task. Either the sepolia or the shibuya one
![1000005988](https://github.com/user-attachments/assets/03dfe0e1-909f-49e1-b183-4b4b83d530c7)
## go to the watch portal https://watch.testnet.analog.one/#/ and click on smart contract 
![1000005990](https://github.com/user-attachments/assets/0265cf81-0b3f-483d-81c6-4e5a960c365e)
## paste your smart contract, give it a name, select the network, give it a tag and add description
![1000005992](https://github.com/user-attachments/assets/49b63ecf-6b95-49ea-a406-3102ed21a891)
## after clicking on add functions, it will ask you for ABI
## go to the page where you verified your smart contract and scroll down a bit
![1000005996](https://github.com/user-attachments/assets/c0afe9cf-da7c-4914-9f80-b916670d008f)
## paste the ABI code and follow the screenshots below to complete the listing task
![1000005998](https://github.com/user-attachments/assets/9ceb0f97-8b5c-4dc2-9432-91b4e9de5032)
![1000006001](https://github.com/user-attachments/assets/991e8e61-3080-491c-8a11-5dc6903436d1)
![1000006003](https://github.com/user-attachments/assets/bf50de43-d15e-40ec-a815-3bc676dbaac1)
## that's all for listing smart contract just wait for some hours and check your point.

# Now let's Build a view
## take note of these three tabs on the interface
![1000006005](https://github.com/user-attachments/assets/8fef2cbb-31d7-4e74-a98f-f6397859ca20)
## under smart contract are lists of deployed smart contracts that anyone can create a view from
## under your query is where the functions you selected will show
## under console is where you test the functions you've selected befor deploying the view
![1000006007](https://github.com/user-attachments/assets/d94d7ed3-f989-47bf-84ca-a50e8f8e2394)
## 1) you select a smartcontract and it will drop down its list of functions 
## 2) you select a function
## 3) check the output of the function. if it requires address, paste your metamask wallet address there and if it requires int or uint just put a number there. if it doesn't require anything like the one above, just leave it.
# Errors
## there are 3 kinds of errors you may face while building view
## 1) error of functions: some functions have errors in their smart contract just leave them
## 2) error of an existing deployment: solve this by adding other functions from other contracts to make your deployment unique
## 3) errror of inputs: solve this by choosing functions that doesn't require arguments or input
![1000006015](https://github.com/user-attachments/assets/7b639789-6468-4e40-901f-97178ac8e0af)
![1000006017](https://github.com/user-attachments/assets/0e94b28d-6ac2-4a5a-bf6c-c85a58c93269)
![1000006019](https://github.com/user-attachments/assets/9e0d7442-81d8-4935-b268-32c1f5f88da4)
## however, input errors are easy to solve. if it asked for address put your metamask and if it asked for uint put any number there
![1000006021](https://github.com/user-attachments/assets/ba7a99e0-edbb-4b64-801c-134bd4ea1b1f)
# for easiness, look for the following functions and chosose them
## balanceOf(requires address), maxSupply, totalmint, tokenUri(requires uint), ownerOf(requires uint), feeGrowth, liquidity, getPairs. if anyone of them you chose already exists combine it with another one(s) from a different contract.
## the example below is a combination of 3 different functions from 3 different contracts.
![1000006023](https://github.com/user-attachments/assets/839d005c-4ed3-4e35-93f7-ad4ecddac190)

## then continue when the console brings a green check
![1000006025](https://github.com/user-attachments/assets/96f3d784-a86b-4aa4-bd52-caae5272a742)
![1000006027](https://github.com/user-attachments/assets/93681451-62e1-483c-beab-b4ddbcf76fec)
![1000006031](https://github.com/user-attachments/assets/6909557a-06e4-459a-a13c-4c5b47c88783)
![1000006033](https://github.com/user-attachments/assets/514576ea-6a19-43e6-88c3-4eff507a9d8a)

# Lets Fund View
