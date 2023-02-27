# MADMetaverse NFT Alpha Test Summary

This repository contains a Jupyter Notebook summarizing the alpha tests for the MADMetaverse NFT project, a GameFi platform. The summary is based on transaction data collected on the Goerli Testnet, and aims to estimate the transaction costs if the project were to be deployed on the Ethereum Mainnet.

Prerequisites
To run the code in the notebook, you will need the following packages:

- web3 (for interacting with Ethereum and Web3 APIs)
- pandas (for data analysis and manipulation)
- requests (for making HTTP requests)
- decimal (for accurate decimal arithmetic)
- json (for JSON encoding and decoding)

You will also need to have accounts on Etherscan, Infura and Moralis, and obtain your respective API keys.

## Installation

1. Clone this repository to your local machine:
```git clone https://github.com/<your-username>/madmetaverse-alpha-summary.git```
2. Install the required packages:
```pip install -r requirements.txt```
3. Download the transaction data CSV file(s) from Etherscan and place it in the 'data' folder.
4. Create the madTX.xlsx file in the data folder. This file should contain all of the transaction data combined into a single sheet and filtered to only include transactions that use the "Evolve" method.
5. Open the Jupyter Notebook:
```jupyter notebook```
6. Navigate to the madmetaverse_alpha_summary.ipynb file and open it.

## Usage
Update the API keys in the notebook with your own Etherscan, Infura and Moralis API keys.

Run the notebook cells in order to retrieve the transaction data and estimate the transaction costs.

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Acknowledgments
- The MADMetaverse team for providing access to their alpha test platform.
- Infura and Moralis for providing their APIs for Ethereum and Web3 development.
- The open-source community for developing the Python packages used in this project.
