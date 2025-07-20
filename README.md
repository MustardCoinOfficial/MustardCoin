# 🟡 MustardCoin (MTC)

Yes, it’s exactly what you think it is — a Bitcoin fork meme coin based entirely around the legendary mustard meme. 🍯🌭

This is **MustardCoin**, a fun altcoin built for memes, mining, and maybe... mooning? Who knows. Dive in and spread the mustard.

---

## 📦 Download

Grab everything you need here:  
🔗 [MustardCoin MediaFire Folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin)

---

## 🚀 How to Run a Node

### 📡 Hosting a Public Node

1. **Port forward** TCP port `8591` on your router.
2. Download and extract `bin.zip` from the [MustardCoin folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin).
3. Launch the node by running `runnode.bat`.
4. Share your **public IP** and port (`8591`) to let others connect to your node.

---

### 🔒 Running a Private Node (Peer Mode)

1. Download a file named `mustardcoin.conf` (available in the MediaFire folder).
2. Place it in:  C:\Users<your-username>\AppData\Local\MustardCoin
3. In `mustardcoin.conf`, add a line like this to connect to a peer: -addnode=<public-node-ip>:8591
4. Set a secure `rpcpassword` in the `.conf` file.
5. Launch `runnode.bat` or double-click `mustardcoin-qt.exe` to start the node or GUI.

---

## ⛏️ Mining MustardCoin

1. Download and extract `cpuminer-opt.zip` from the [MustardCoin folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin).
2. Ensure the MustardCoin node has run at least once so the config directory is created.
3. Place `mustardcoin.conf` in: C:\Users<your-username>\AppData\Local\MustardCoin
4. Set your `rpcpassword` inside `mustardcoin.conf`.
5. Open `run.bat` in the cpuminer-opt folder with Notepad.
6. Update the following in `run.bat`:
- Match the `rpcpassword` to your config
- Replace the MTC address with one from your MustardCoin wallet
7. Save the file and double-click `run.bat` to begin mining!

**Note:** If you see an error about the node not connecting, make sure the node is running and wait a few seconds.

## 🌐 Post Your Public Nodes Here!
https://discord.gg/MkT3qH57HM


