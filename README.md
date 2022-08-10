	"CREATE YOUR OWN PRIVATE BLOCLCHAIN"

First I make folders on local disk D
like this D:\Blockchain\PrivateBlockchain

And then I made genesis.json file in PrivateBlockchai
Then I run "geth --datadir PrivateBlockchain init .\genesis.json"
Then this (Successfully wrote genesis state) has print.

Then I run "geth --datadir .\PrivateBlockchain\"
My private Blockchain start successfully

	"BLOCKCHAIN RUNNING SUCCESSFULLY"

Then I stopped this "geth --datadir .\PrivateBlockchain\" and run "geth --datadir  .\PrivateBlockchain\ --nodiscover" for minning.

	"MINNING RUNNING SUCCESSFULLY"

After this I *open one more windows PowerShell* (but must should be memories your path those will be, where in chaindata folder
(like this D:\blockchain\PrivateBlockchain\PrivateBlockchain\geth\chaindata) this path is mine and when you go in right path) you run "geth attach".

And then I run javascript code "eth.accounts" and of this reuslt is [].
So I run "personal.newAccounts" and then enter again enter and my account has made and that account, I can see in keystore folder in my directory.

After this I run some commands, those are writen below:

1 eth.coinbase, this result was my account.

2 miner(This command is not for compulsory, it's opptional)

3 miner.setEtherbase(eth.accounts[0]), this result was true.

4 miner.start(1), This result was null.

5 web3, after this alot commands & functions has appeard on my screen.

6 web3.eth.getBalance(eth.accounts[0]), this result was ether those who are mining but that's form in Wei.

7 web3.fromWei(eth.getBalance(eth.accounts[0]), "ether"), This result was also ether but that's form was in ether.(optional)

8 web3.fromWei(eth.getBalance(eth.accounts[0]), "finney"), This result was also ether but that's form was in finney.(optional)


	"CONGRATULATIONS" YOUR PRIVATE BLOCKCHAIN HAS RUNNING SUCCESSFULLY

This process is not difficult, it's so easy.
First you open Windows PowerShell and run commands one by one. But this must should be memories you will open two windows PowerShell. In first you run blockchain and this PowerShell will also for
minning and in second PowerShell you run differents commands for different functions. First PowerShell will be main PowerShell. 

						"COMPLETED"
