# assignment3-Blockchain

## AITUSE2315  
 
This project includes:  
- Core ERC-20 token functionality.  
- Event-based transaction logging.  
- Metadata retrieval for transactions, such as participant addresses and block timestamps.

---

## **Features**
1. **ERC-20 Token**  
   A fully compliant ERC-20 token with an [initial token supply].  

2. **Event Logging**  
   The contract logs the following data for each transaction:
   - Sender's address
   - Receiver's address
   - Amount of tokens transferred
   - Transaction timestamp  

3. **Retrieve Metadata**  
   Functions to fetch information such as:  
   - Block timestamps in a human-readable format.  
   - Addresses of transaction participants.

4. **Custom Functionality**  
   Unique features like `functionName` provide [describe additional functionality].

---

## **Prerequisites**
Before deploying this project, ensure you have the following tools installed:  
- **Solidity Compiler**: Version `^0.8.x`.  
- **Remix IDE**: To write, compile, and deploy the contract.  
- **MetaMask**: For interacting with the deployed contract.  
- **OpenZeppelin Contracts**: A library for ERC-20 implementation.

---

## **Contract Overview**
### **Functions**
#### **Constructor**  
Initializes the token with the following parameters:
- Name: AITUSE2315
- Symbol: MTK
- Initial Supply: 2000 tokens

#### **Function Name**
Description of functionality, e.g.:  
- Logs transaction details.  
- Sends tokens with additional metadata.

### **Events**
#### **Event Name**  
Logs:  
- Sender's address  
- Receiver's address  
- Amount of tokens transferred  
- Block timestamp  

---

## **Deployment Instructions**
1. Open [Remix IDE](https://remix.ethereum.org/).  
2. Create a new file: `[filename].sol`.  
3. Copy the contract code into the file.  
4. Compile the contract using Solidity Compiler version `^0.8.x`.  
5. Deploy the contract using JavaScript VM, MetaMask, or an Ethereum testnet (e.g., Goerli).  

---

## **Usage**
### **Interact with the Contract**
1. Install MetaMask: [MetaMask](https://metamask.io/).  
2. Connect to an Ethereum testnet.  
3. Add the deployed contract address to MetaMask to interact with your tokens.  

### **Test the Contract**
- Call the `transferWithDetails` function with the recipient's address and token amount.  
- Use `getBlockTimestamp` to fetch the block's timestamp.  

---

## **Project Structure**
```plaintext
├── contracts/
│   ├── ContractName.sol       // Smart contract source code  
├── images/
│   ├── screenshot1.png        // Screenshots of the interface  
├── README.md                  // Project documentation  
├── LICENSE                    // Project license  

