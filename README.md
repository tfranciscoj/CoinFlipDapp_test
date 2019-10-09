# Dapp_test

Code in home is imported directly from Superblocks.
This is an experiment to setup dapp outside Superblocks. 
Notes:
1. 1st attempt: submit button does not work, but contract
balance works fine.
2. 2nd attempt: after running: "web3.currentProvider.enable()"
on js console in same window that Dapp_test webpage submitt
button works but balance does not update and win or lose message
does not appear.
3. 3rd attempt: following Filip's advice added

let accounts=web3.eth.accounts;

in getResult() and that fixed it. Now works.
