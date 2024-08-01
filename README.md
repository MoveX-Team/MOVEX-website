# MOVEX-website

MOVEX Mint

    A revolutionary platform for minting AI-generated art,built using Solidity,Move language,and ChatGPT.

Project Description 
    MoveX Mint is an innovative platform that leverages the power of artificial intelligence to generate unique digital art.Our platform 
  utilizes Solidity for smart contracts, Move language for custom trancsactions, ChatGPT for AI art generation.This project aims to provide 
  a seamless experience for users to mint and collect exclusive AI-generated art pieces.

Table of Contents

1.Project Description
2.Features 
3.Technology Stack
4.Installation
5.Usage
6.Smart Contracts
   * Solidity Contracts
   * Move Contracts
7.Contributing
8.Credit
9.Licence


Features
* AI-Powered Art Generation: Leverage ChatGPT to interpret and generate digital art.
* NFT Creation: Use Solidity for Ethereum-based NFT minting and Move for additional blockchain functionalities.
* Interactive Web Interface: Simple and intuitive UI for creating and managing digital art and NFTs.

Technology Stack
* Frontend: React.js, HTML, CSS
* Backend: Node.js, Express.js
* AI: OpenAI ChatGPT
* Smart Contracts:
    * Solidity: For Ethereum NFT minting and management.
    * Move: For additional blockchain operations and functionalities.
* Blockchain: Ethereum, Move-based blockchain (e.g., Aptos)
* Database: MongoDB

Installation
   To run MoveX Mint ,follow these steps 
   
     * Install Node.js and npm(if you haven't already)
     
	 * Clone the repository using (git clone https://github.com/yourusername/movex.gitcd movex)

     * Navigate to the directory using `cd movex-mint
	 
	 * install dependencies using 
         - For The Frontend (cd clientnpm install)

         - For  The  Backend (cd ../servernpm install)

         - For Solidity smart contracts (cd ../smart-contractsnpm install)

         - For Move smart contracts (cd ../move-contracts# Follow instructions specific to the Move blockchain environment setup.)
         
     * Set Up Environment Variables

          Create .env files in client, server, and other relevant directories. 
          Use .env.example as a reference.Example .env file
           (REACT_APP_API_URL=http://localhost:5000MONGODB_URI=mongodb://localhost:27017/movexETHEREUM_PRIVATE_KEY=your_private_key
            MOVE_CONTRACT_ADDRESS=your_move_contract_address)
      * Start Development Servers

        -Start the backend server:
           (  cd server 
             npm start )
        -Start the frontend development server:
             ( cd ../client
                npm start )
        -For Solidity smart contracts, compile and deploy:
            ( cd ../smart-contracts
              truffle compile
              truffle migrate --network development )
        -For Move smart contracts, compile and deploy using Move CLI tools:
          (  cd ../move-contracts
             move-cli run --path <path-to-your-move-script>  )




 Usage
 
1.Generate Art

 * Access the art generation page on your local server (http://localhost:3000).
 * Input your creative prompt and submit it.
 * ChatGPT will generate and display the artwork.
   
2.Mint NFTs

 * After generating art, navigate to the minting page.
 * Connect your Move wallet (e.g., Razor).
 * Follow the instructions to mint the artwork as an NFT.


Smart Contracts

  *Solidity Contracts
    -Location: smart-contracts/contracts
    -Tools: Truffle or Hardhat
     -Setup:
         Compile contracts: truffle compile or npx hardhat compile
         Deploy contracts: truffle migrate or npx hardhat run scripts/deploy.js --network localhost
         
  * Move Contracts
     -Location: move-contracts/src
     -Tools: Move CLI
     -Set up:
         compile contracts: move-cli compile
         Deploy contracts: move-cli run --path <path-to-your-move-script>




             
