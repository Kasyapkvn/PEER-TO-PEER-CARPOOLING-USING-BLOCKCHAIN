# Peer-to-Peer Carpooling using Blockchain

A decentralized ride-sharing platform using Django for the web app and an Ethereum smart contract for storing ride data. This project was built to explore how blockchain can increase security and trust in carpooling systems.

## 🚀 Tech Stack

-   **Backend:** Python, Django
-   **Frontend:** HTML, CSS
-   **Blockchain:** Solidity, Ethereum
-   **Tools:** Truffle, Ganache, Web3.py

## ⚙️ Getting Started

### Prerequisites

Make sure you have these installed:
-   Git
-   Python 3.8+
-   Node.js (specifically **v12.13.1** from the `.msi` file in this repo)
-   Truffle (`npm install -g truffle`)
-   Ganache (download from the Truffle website)

### Quick Start Guide

1.  **Clone the repo**
    ```bash
    git clone [https://github.com/Kasyapkvn/PEER-TO-PEER-CARPOOLING-USING-BLOCKCHAIN.git]
    cd PEER-TO-PEER-CARPOOLING-USING-BLOCKCHAIN
    ```

2.  **Start your local blockchain**
    -   Open and run **Ganache**.

3.  **Deploy the smart contract**
    -   Open a new terminal and run:
    ```bash
    truffle migrate
    ```

4.  **Set up the web app**
    -   In the same terminal, create a virtual environment and install packages:
    ```bash
    # Create and activate virtual environment (Windows)
    python -m venv venv
    .\venv\Scripts\activate

    # Install Python packages
    pip install -r requirements.txt
    ```

5.  **Run the server**
    ```bash
    python manage.py runserver
    ```
    -   Now open your browser to `http://127.0.0.1:8000/`

---
