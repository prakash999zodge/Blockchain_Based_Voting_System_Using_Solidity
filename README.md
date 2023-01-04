# Blockchain_Based_Voting_System_Using_Solidity
Hey folks... I have created Voting System using front end as HTML and backend as Solidity language which is new technology called blockchain
<br>


## Pre-requisite ##
  * Install Ganache https://trufflesuite.com/ganache/
  * Install Metamask Google Chrome Extension https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en
  * Install Visual Studio Code https://code.visualstudio.com/download
      * Download Extensions of VS Code
          * HTML
          * HTML Live Server

## Steps to Perform ##
  1. Download & Extract zip file
  2. Open Remix IDE https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null
      1. Load/Upload ballot.sol
      2. Go to Compile section
      3. Select suitable Compiler version
      4. & click 'Compile ballot.sol'
      5. Copy 'ABI Code' from the same Compile panel
      
  3. Start Visual Studio Code & Open folder 'Code'
      1. Paste 'ABI Code' into variable 'ballotABI' of Code/index.html file
      2. Click on 'Index.html' then click 'Go Live'
      3. Then we have to add some ether to the 'Metamask' with the help of 'Ganache'
          1. Click on 'Metamask'
          2. Enable Test Networks
          3. Copy private key from Ganache and
          4. Click 'Import Account' and paste private key in the textfield
          5. Repeat above 'c' & 'd' until we get 1 admin account and minimum 3 voters account
      4. Select 'Metamask' from extensions of chrome and select Admin's Account
      5. Now you are good to go with

Thank you
