# MustardCoin
Yes this is exactly what you think it is. This is a bitcoin fork altcoin based around the meme about mustard.

You can download the source code and software from this link https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin

To host a public node all you need to do is port forward the port 8591 and download the zip called bin and extract it then run the mustardcoin node by opening the file called runnode.bat in the extracted folder
then you can share your public ip and port to let other peers connect to your node.

Or if you aren't going to host a public node just look for a file called mustardcoin.conf in https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin and copy and paste it into 
the directory C:\Users\(youruser)\AppData\Local\MustardCoin and inside the conf file add a line called -addnode=(a public node ip:port) to connect to a peer and also make sure to change the rpc password then run the runnode.bat or open the mustardcoin-qt.exe to open the mustardcoin GUI.

To mine all you have you to do is go to https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin and look for a zip called cpuminer-opt
then after download it and extract it to wherever you feel like. Then go back to https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin
and look for a file called mustardcoin.conf and copy and paste it into the directory C:\Users\(youruser)\AppData\Local\MustardCoin
(if you don't have this directory make sure you have run the node via gui or cli at least one time) then open the conf file and change the
rpc password. Now just go back to the cpuminer-opt extracted folder and edit the run.bat with notepad and go ahead and change the rpc password 
to the rpc password in your mustardcoin.conf and also change the mtc address to one you got from your wallet in the gui or cli. Now just
save the run.bat changes and then open the run.bat which should start mining as long as you keep the mustardcoin node active via 
cli or gui. if you get a error talking about mustardcoin not connecting then just make sure the node is active and wait it out it should just
go away after a bit.
