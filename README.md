# Bootstrap

This repository contains the bootstrap chain files for the Avian blockchain. Using these files helps shorten the amount of time it takes to sync the wallet since you don't need to sync the blockchain from scratch.

---

## Instructions
If you have never run the Avian wallet, follow the second set of directions below. If you have already run the Avian wallet before, follow the first set of directions below.

#### If you have *already* run the Avian wallet:

1. Download the [latest bootstrap files](https://wallet.avn.network/bootstrap/Avian.zip).
1. Find the downloaded *Avian.7z.001* file and open with 7Zip. 
1. Close and quit the Avian wallet if it is running.
1. Navigate to your OS's respective data directory.

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\Avian\`
		1. Or paste `%appdata%\Roaming\Avian\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/Avian/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/.avian/`
1. Remove all files and folders other than `wallet.dat`. **DO NOT** delete the *wallet.dat* file as it contains the private keys for your funds. Deleting these will result in a loss of funds.
1. Extract the folder and files into the Avian wallet's data directory that you just removed folders from.
1. If you do not have the [latest Avian wallet](https://github.com/AvianNetwork/Avian/releases/tag/v4.1.0), download and install it.
1. Run the wallet, and syncing should begin at the bootstrap's last block.

#### If you have *never* run the Avian wallet:

1. Download the [latest bootstrap files](https://github.com/AvianNetwork/Bootstrap/releases).
1. Find the downloaded *Avian.7z.001* file and double-click. This will unzip the file and show a folder named *Avian*.
1. From a dos prompt or terminal create the Avian folder: *mkdir %appdata%/Avian* (Windows) **mkdir ~/.avian** (Linux).

	1. For Windows: `C:\Users\[YourUsername]\AppData\Roaming\`
		1. Or paste `%appdata%\Roaming\` into the file explorer path field
	1. For MacOS: `~/Library/Application Support/`
		1. Open Finder and in the program menu select *Go* > *To Folder* and enter the above path.
	1. For Linux: `~/`
		1. **Note**: For Linux you must rename the *Avian* folder to `.avian`
1. Download the [latest Avian wallet](https://github.com/AvianNetwork/Avian/releases/tag/v4.1.0).
1. Install and run the wallet. Syncing should begin at the bootstrap's last block.
