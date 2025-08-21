# Blockchain Explorer & Validator

A web-based, interactive application that demonstrates the core concepts of a simple **Proof-of-Work blockchain**.  
Users can visualize a live blockchain, mine new blocks, and validate the integrity of an entire chain from an uploaded file.


##  Features
- Visualize a live blockchain 
- Mine new blocks with Proof-of-Work (SHA-256)  
- Validate the integrity of an uploaded blockchain file  


## Technical Details

### Backend
- **Runtime:** Node.js  
- **Framework:** Express.js  

### Frontend
- **Technologies:** HTML5, CSS3  

### Hashing Algorithm
- **Algorithm:** SHA-256  
- **Hashing Process:**  
  Each block's hash is generated from:
  - Block index  
  - Timestamp  
  - Data  
  - Previous block’s hash  
  - Nonce (Proof-of-Work)  

## ⚡ Getting Started

### ✅ Prerequisites
- Install [Node.js](https://nodejs.org/) (includes npm)

### 📦 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/keshavgoelkg2000/blockchain-explorer.git
```

Install Dependencies:
 
```bash
npm install express
```

Run the server:
```bash
node server.js
```

Open the application:
The terminal will display:

```bash
Server is running on http://localhost:8080
```

Navigate to http://localhost:8080 in your browser.