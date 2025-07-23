# 🟡 MustardCoin (MTC)

Yes, it’s exactly what you think it is — a Bitcoin fork meme coin based entirely around the legendary mustard meme.

> **Note:** This guide is meant for **Windows devices only**.

---

## 📦 Download

Grab everything you need here:  
🔗 [MustardCoin MediaFire Folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin)

> *(Some files are over 100MB, so they couldn't be hosted directly on GitHub.)*

---

## 🚀 How to Run a Node

### 📡 Hosting a Public Node

1. **Port forward** TCP port `8591` on your router.
2. Download and extract `bin.zip` from the [MustardCoin folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin).
3. Launch `mustardcoin-qt.exe` **once** to generate the config directory.
4. After it loads, **close the app**.
5. Download the `mustardcoin.conf` file from the MediaFire folder.
6. Place `mustardcoin.conf` in:  
   `C:\Users\<your-username>\AppData\Local\MustardCoin`
7. Open the file and set a secure `rpcpassword` (and optionally a `rpcuser`).  
   Example:
   ```ini
   rpcuser=mustarduser
   rpcpassword=your_secure_password
   ```
8. Save the file.
9. Reopen the node by running `runnode.bat` (or `mustardcoin-qt.exe` directly).
10. Share your **public IP** and port (`8591`) with others so they can connect to your node.

---

### 🔒 Running a Private Node (Peer Mode)

1. Download and extract `bin.zip` from the [MustardCoin folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin).
2. Launch `mustardcoin-qt.exe` **once** — this will create the config directory.
3. After it loads, **close the app**.
4. Download the `mustardcoin.conf` file (available in the MediaFire folder).
5. Place `mustardcoin.conf` in:  
   `C:\Users\<your-username>\AppData\Local\MustardCoin`
6. In `mustardcoin.conf`, add a line like this to connect to a peer:  
   ```ini
   addnode=(public-node-ip):8591
   ```
   > By default, there is already a node added — **do not delete it**.
7. Set a secure `rpcpassword` in the `.conf` file.
8. Relaunch `mustardcoin-qt.exe` to start your node with peer settings.

---

## ⛏️ Mining MustardCoin

1. Download and extract `cpuminer-opt.zip` from the [MustardCoin folder](https://www.mediafire.com/folder/1nx9no4h8u5rh/MustardCoin).
2. Make sure the MustardCoin node has run at least once so the config directory is created.
3. Place `mustardcoin.conf` in:  
   `C:\Users\<your-username>\AppData\Local\MustardCoin`
4. Set your `rpcpassword` inside `mustardcoin.conf`.
5. Open `run.bat` in the `cpuminer-opt` folder using Notepad.
6. Update the following in `run.bat`:
   - Match the `rpcpassword` to your config
   - Replace the MTC address with one from your MustardCoin wallet
7. Save the file and double-click `run.bat` to begin mining!

> **Note:** If you see an error about the node not connecting, make sure the node is running and wait a few seconds.

---

## 🌐 Post Your Public Nodes Here!

👉 [Join the Discord](https://discord.gg/MkT3qH57HM)
