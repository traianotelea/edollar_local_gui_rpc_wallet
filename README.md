# edollar local gui rpc wallet

This guide will be updated based on user feedback, so please report the bugs.

How to use : 

Copy the files to your edollar folder - run start_wallet.bat, wait for the daemon to sync with the network.

Start_wallet.bat will start :<br> 
edollar daemon<br>
edollar rpc daemon<br>
chrome with websecurity off - <strong>IT IS NOT SAFE TO USE THIS INSTANCE OF CHROME FOR BROWSING THE INTERNET</strong><br>

<strong>If you already have a cli-wallet, copy the 3 wallet files to /wallets folder to use it.</strong><br>
By 3 wallet files I mean : there must be 3 different files that contain your wallet filename :<br>
mywallet<br>
mywallet.address.txt<br>
mywallet.keys<br>
<br>
The start_wallet script works on WINDOWS ONLY and needs Chrome to be installed. 

If Windows asks you about network permission for edollard.exe and edollar-wallet-rpc.exe, grant them.

If you are concerned about the security of your coins : <strong>This wallet is a wrapper for the existing commands in the rpc daemon. By itself, it just sends commands to/from the rpc daemon and shows the info on screen.</strong>

After you make a payment, wait at least 2-3 blocks for the balance to get updated.

Screenshots:

![screen1](screens/1.PNG)<br>
![screen2](screens/2.PNG)<br>
![screen3](screens/3.PNG)<br>
![screen4](screens/4.PNG)<br>
![screen5](screens/5.PNG)<br>
![screen6](screens/6.PNG)<br>
