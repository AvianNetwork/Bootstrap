# Bootstrap

This repository contains the bootstrap chain files for the Avian blockchain. Using these files helps shorten the amount of time it takes to sync the wallet since you don't need to sync the blockchain from scratch.

---

## Instructions
If you have never run the Avian wallet, follow the first set of directions below. If you have already run the Avian wallet before, follow the second set of directions below.

#### If you have *already* run the Avian wallet:

1. Download the [latest bootstrap files](https://wallet.avn.network/bootstrap/Avian.zip).
1. Find the downloaded *Avian.zip* file and double-click. This will unzip the file and show a folder named *Avian*.
1. Close and quit the Avian wallet if it is running.
1. Navigate to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\Avian\`
		1. Or paste `%appdata%\Roaming\Avian\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/Avian/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/.avian/`
1. Remove folders `blocks/` and `chainstate/` and `powcache.dat` file. **DO NOT** delete the *wallet.dat* file as it contains the private keys for your funds. Deleting these will result in a loss of funds.
1. Inside the downloaded *Avian* folder, there are the `blocks/` and `chainstate/` folders and `powcache.dat` file. Move these two folders and powcache.dat into the Avian wallet's data directory that you just removed folders from.
1. If you do not have the [latest Avian wallet](https://www.avn.network/start-mining), download and install it.
1. Run the wallet, and syncing should begin at the bootstrap's last block.

#### If you have *never* run the Avian wallet:

1. Download the [latest bootstrap files](https://github.com/AvianNetwork/Bootstrap/releases).
1. Find the downloaded *Avian.zip* file and double-click. This will unzip the file and show a folder named *Avian*.
1. Move the *Avian* folder to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\`
		1. Or paste `%appdata%\Roaming\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/`
		1. **Note**: For Linux you must rename the *Avian* folder to `.avian`
1. Download the [latest Avian wallet](https://www.avn.network/start-mining).
1. Install and run the wallet. Syncing should begin at the bootstrap's last block.
