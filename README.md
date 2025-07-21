<img width="1920" height="1080" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/e089a412-e2ab-4289-8bcd-f98d045e8db8" />
<img width="1920" height="1080" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/8f40b2ae-fc59-4334-a4e5-3664595d4500" />
<img width="1920" height="1080" alt="Screenshot (150)" src="https://github.com/user-attachments/assets/752a04ea-885b-4288-aebc-a8fc10174385" />
<img width="1920" height="1080" alt="Screenshot (151)" src="https://github.com/user-attachments/assets/4d60d3ad-f661-47d1-8cbd-69b2be01a1a3" />
<img width="1920" height="1080" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/d4ec923c-154a-4dad-8914-cc2aa0d54c9e" />

📁 Decentralized Google Drive using Blockchain, Django & IPFS

🚀 A secure, decentralized alternative to traditional cloud storage platforms like Google Drive — built using **Ethereum**, **IPFS**, **Django**, and **React**.

---

🧠 Project Overview

A fully decentralized cloud storage solution that ensures **user ownership**, **secure access control**, and **tamper-proof file storage**.  
This system utilizes:

- **Smart Contracts (Solidity)** for secure permissions  
- **IPFS** for file storage  
- **Pinata API** for IPFS file pinning  
- **Django Backend** for logic support  
- **React + Metamask** for user interface and wallet interaction

---

💻 Tech Stack

| Layer        | Technology Used                     |
|--------------|-------------------------------------|
| 🖥️ Frontend   | React.js, JavaScript, HTML5, CSS3   |
| ⚙️ Backend    | Python, Django                      |
| 🔐 Blockchain | Solidity, Hardhat, Ethereum         |
| 🧾 Storage    | IPFS (InterPlanetary File System) + Pinata |
| 👛 Wallet     | Metamask + Ethers.js                |

---

✨ Features

- 📤 Upload files to IPFS via Pinata  
- 🛡️ File hash stored on Ethereum blockchain  
- 👥 Grant & revoke file access using smart contracts  
- 🧾 View only authorized files  
- 🧠 Smart contract-powered access management  
- 🖼️ Sleek, interactive UI with Metamask integration  

---

📦 Smart Contract Highlights (Upload.sol)

solidity
-function add(address _user, string memory url) external;
-function allow(address user) external;
-function disallow(address user) public;
-function display(address _user) external view returns(string[] memory);
-function shareAccess() public view returns(Access[] memory);

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/yourusername/decentralized-drive.git
cd decentralized-drive

2️⃣ Install dependencies
npm install
cd backend
pip install -r requirements.txt

3️⃣ Compile & Deploy Smart Contracts
cd blockchain
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost

4️⃣ Start Local Blockchain
npx hardhat node


5️⃣ Run Django Server
cd backend
python manage.py runserver

6️⃣ Run React Frontend
cd ../
npm start

🔑 Pinata API Setup
1. Create an account on Pinata
2. Get your API Key & Secret
3. Paste them inside FileUpload.js
pinata_api_key: `your_api_key`,
pinata_secret_api_key: `your_secret_key`,

📚 Project Structure
├── backend/
│   └── Django backend files
├── blockchain/
│   └── Upload.sol (Smart Contract)
├── frontend/
│   └── React App (App.js, FileUpload.js, Display.js, Modal.js)

📈 Future Scope
🔒 File encryption layer before IPFS upload
📱 Mobile app support using React Native
🪪 Decentralized Identity (DID) integration
☁️ Integration with Filecoin for persistent pinning
🕵️ Zero-Knowledge Proofs for privacy-preserving access 





