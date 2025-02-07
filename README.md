MyTitleLock1 (Soon to be MyLockChain.io)
MyTitleLock1 is a decentralized application (dApp) that secures title deeds and important documents by leveraging blockchain and the InterPlanetary File System (IPFS). Once testing is complete, the project will be rebranded as MyLockChain.io.

Table of Contents
Overview
Features
How It Works
Prerequisites
Installation & Deployment
Usage
Customization
Contributing
License
Overview
MyTitleLock1 (future MyLockChain.io) provides a secure, tamper-proof solution for managing title deeds and other critical documents. By uploading your file, the application:

Hashes the document to create a unique digital fingerprint.
Pins the file to IPFS for decentralized, censorship-resistant storage.
Registers the file’s hash on the Ethereum blockchain to ensure immutability and verifiability.
Features
Multi-File Support:
Upload various file types including:

PDF files (.pdf)
Text files (.txt)
Solidity source files (.sol)
Images (.jpg, .jpeg, .png)
Videos (.mp4)
(Additional file types can be added as needed)
Decentralized Storage:
Uses IPFS to store files in a distributed network, ensuring high availability and resistance to censorship.

Blockchain Registration:
Records the document’s unique cryptographic hash on the Ethereum blockchain, creating a permanent and verifiable record.

Wallet Integration:
Supports popular blockchain wallets like MetaMask and Coinbase Wallet for secure transactions and gas fee payments.

PayPal Integration:
For larger files (beyond a free threshold), PayPal is used to handle the payment for file pinning.

User-Friendly Steps:
The dApp guides users through six simple steps:

Prepare Your Document: Choose a file to protect.
Pin Your Document on IPFS: Upload the file and generate its IPFS hash.
Install & Fund Your Wallet: Set up and fund a blockchain wallet.
Connect Your Wallet: Link your wallet to the dApp and understand gas fees.
Register on the Blockchain: Store the document hash on Ethereum.
Save Your Transaction Receipt: Keep a record for future verification.
How It Works
File Upload & Hashing:
When you select a file (supported types include PDF, TXT, SOL, JPG, JPEG, PNG, MP4), the application uploads it to IPFS. It then computes a cryptographic hash (SHA-256) of the file. This hash acts as a unique digital fingerprint; even the slightest alteration in the file will result in a completely different hash.

IPFS Storage:
The file is pinned on IPFS, ensuring it is stored in a decentralized manner and is always available.

Blockchain Registration:
Your wallet (MetaMask or Coinbase Wallet) is used to sign a transaction that registers the file's hash on the Ethereum blockchain. Gas fees (paid in ETH) compensate network validators for processing the transaction.

Verification:
Later, you or any third party can verify the file’s authenticity by comparing a locally computed hash with the hash stored on the blockchain.

Prerequisites
Domain Ownership:
(For future branding as MyLockChain.io) Ensure you own the domain and have configured it appropriately (e.g., using Netlify for hosting and DNS management).

Ethereum Wallet:
Install and set up a blockchain wallet such as MetaMask or Coinbase Wallet.

ETH Funds:
Ensure your wallet is funded with enough ETH on the Ethereum mainnet to cover gas fees.

Developer Tools:
Basic familiarity with HTML, CSS, JavaScript, and the Ethereum blockchain.

Installation & Deployment
Clone the Repository:

bash
Copy
git clone https://github.com/yourusername/MyTitleLock1.git
cd MyTitleLock1
Configure Environment Variables:

Replace REPLACE_WITH_YOUR_PAYPAL_CLIENT_ID in the PayPal SDK script URL with your actual PayPal client ID.
Update any API keys (for example, the Etherscan API key) in the code.
Deploying on Netlify:

Push your repository to GitHub (or your preferred Git provider).
Log in to Netlify and connect your repository.
Configure the build settings if needed and deploy your site.
Use Netlify’s DNS settings to manage your domain (MyTitleLock1.io now, and later MyLockChain.io).
Testing on Ethereum:

Ensure your wallet is connected to the Ethereum mainnet (or a testnet if configured for testing).
Verify that your dApp interacts correctly with the blockchain by running through the upload and registration process.
Usage
Step 1 – Prepare Your Document:
Select a file using the file input. Supported file types are listed in the interface.

Step 2 – Pin Your Document on IPFS:
Click the Upload and Hash Document button. Your file will be uploaded to IPFS, and a unique hash will be generated.

Step 3 – Install & Fund Your Wallet:
Follow the instructions to set up your blockchain wallet and add ETH to cover gas fees.

Step 4 – Connect Your Wallet:
Click the Connect Wallet button and approve the connection in your wallet. Learn about gas fees and why they are needed.

Step 5 – Register on the Blockchain:
After the file is uploaded and hashed, review the file summary displayed above the Register on Blockchain button. Click the button to record your document’s hash on Ethereum.

Step 6 – Save Your Transaction Receipt:
A receipt (including a QR code and transaction details) is generated. Save this receipt for future verification.

Optional Features:
Additional buttons (styled in blue) provide extra functions such as viewing more information about IPFS and document storage.

Customization
Styling:
Update the CSS in the <style> section to adjust colors, fonts, and layout.
Functionality:
Modify the JavaScript functions to extend features such as additional file types, different payment options, or enhanced blockchain interactions.
Rebranding:
When ready to launch as MyLockChain.io, update the title, domain references, and branding elements in the project.
Contributing
Contributions are welcome! If you have suggestions, bug fixes, or new features, please submit a pull request or open an issue.

License
This project is licensed under the MIT License.
