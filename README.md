# Android-Mining
Currrent ccminer, my configs + pool/solo scripts, install command

** Pool and Solo Mining Verus on Android Phones **
Easily switch between Pool and Solo Mining on your farm with simple commands.

This was created out of frustration of not being able to solo mine Verus. Luckpool has "Hybrid" mining but 
if you have enough hashrate to mine several coins per week, the additional reward is not worth it. You can 
make more VRSC using Vipor.net pool mining than you can hybrid mining Luckpool.

While Vipor indicates it supports solo mining, their solo stratum addresses are the same as their various 
pool addresses.  Also, if you compare any "pool" miner with a "solo" miner of similar hashrate, there is 
no difference in payouts.

At the time of this writing, the reward is 3 VRSC per block.

Out of frustration of no solo mining support, I have created my own solo pool. I have built a flexibility into 
my start.sh to allow both a config.json (defaults to Vipor.net) or a config_solo.json which references my personal pool. 

** Cloning and customizing**
1. Clone this repo to your own github account. I copied an ARM optimized version of ccminer from Oink70.
2. Download a QR Code Reader/Creator and create your own QR code for quicker installation per phone.
3. I created my own start.sh which does not include a line allowing for an SSH Key. If you want to control your 
cpus remotely, then you will need to add lines of programming to that affect. Visit https://Oink70/Android-Mining/ and 
check out the readme file. Read it thoroughly regarding SSH.
4. Adjust the ‘config.json’ to your address, port, etc.
5. Adjust the ‘config_solo.json’ to your solo pool address, port, etc.

*** Disclaimer***
I am not a programmer. I do not warranty or guarantee any of this and that you will not struggle through it. 
A fundamental working knowledge of Linux is a necessity.

A stable network (wifi, wired, cellular) is required for any of this to work. 

Following is a series of topics I plan to cover later:
1. Start to finish – Setting up a Verus mining farm using a mining pool.
2. Start to finish – Setting up a solo Verus mining farm.
3. How to connect hundreds of miners to your wifi without crashing the farm.
4. How to remove the batteries from your miners and direct wire them to power including operating voltage (not 5V) and 
tricking the Android into thinking there is a battery present.
5. How to connect your miners to ethernet without an OTG connection.

**** Use all or some of this at your own risk. ****
