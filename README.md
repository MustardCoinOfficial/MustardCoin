🟡 MustardCoin (MTC)
Yes, it’s exactly what you think it is — a Bitcoin fork meme coin based entirely around the legendary mustard meme. 

📦 Download
Grab everything you need here:
🔗 MustardCoin MediaFire Folder

🚀 How to Run a Node
📡 Public Node
Port Forward port 8591 on your router.

Download the bin.zip from the MediaFire Folder and extract it.

Run the node by opening runnode.bat from the extracted folder.

Share your public IP and port (8591) with others so they can connect to your node.

🔒 Private Node / Peer Mode
Download or create a file named mustardcoin.conf (also available in the MediaFire folder).

Place it in:
C:\Users\<your-username>\AppData\Local\MustardCoin

Add this line to the mustardcoin.conf file (replace with a real IP and port):

ini
Copy
Edit
addnode=<public-node-ip>:8591
Also make sure to set a secure rpcpassword in the .conf file.

Launch runnode.bat or open mustardcoin-qt.exe to run the wallet/node GUI.

⛏️ How to Mine MustardCoin
Download cpuminer-opt.zip from the MediaFire Folder and extract it anywhere.

Make sure you've already run the MustardCoin node at least once (GUI or CLI), so it generates the config directory.

Copy mustardcoin.conf to:
C:\Users\<your-username>\AppData\Local\MustardCoin

Edit the mustardcoin.conf file to set a unique rpcpassword.

Open the run.bat file in the cpuminer-opt folder using Notepad.

Update:

The rpcpassword to match the one in mustardcoin.conf

The wallet address (mtc...) to one you control (you can generate it from the GUI/CLI)

Save and run run.bat — mining should start automatically.

If it errors with connection issues, ensure your node is running and give it a moment.
