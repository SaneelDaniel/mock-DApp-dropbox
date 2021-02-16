## `Decentralized File Storage.`

### Welcome to the New World of File Storage & Sharing

    -- This app uses IPFS to store your files in a de-centralized secure file storing network

    -- The files are mapped with the Ethereum Wallet Account that approved the transaction

    -- This ensures no other account can view/tamper with the documents on another account

    -- The contracts are written in Solidity Language, and tested and deployed using Ganache and Truffle Framework

    -- The tests are written using Chai Framework

    -- The Client Side app is written using React.JS & Web3.js


## Screen shots Of the Running App

### HomePage
(The client side front-page)

 ![home-page-image](images/screenshot-homepage-acct2.png)


### File Upload
(The file upload transaction confirmation by metamask)

 ![file-upload-confirmation] (images/screenshot-account2-fileupload-network-confirmation.png)


### Successful Upload Transaction

 ![file-uploaded](images/screenshot-fileuploaded-acct2.png)


### Account Info and separation of document between two accounts

 ![acct-separation-info](images/screenshot-accooun1-homepage.png)


### Shareable hashed Link genereated by IPFS

 ![shaerable-link-content](images/hashed-ipfs-llnk.png)


## Available Scripts

In the project directory, you can run:

### `npm install`

Installs all the necessary packages to run the app i development mode.\

The cosole will show if the packages were successfully installed.\
You will also see any lint errors in the console.

## Starting the Block Chain Network and Deploying the contracts

#### Install Ganache, Truffle Framework, and Metamask Browser Extention

In the project directory, you can run:

### `truffle migrate --reset`

Deploys the contract on the network, and resets any other version of the contract on the network.

### `truffle console`

Open up the truffle console to test or check the network details.

### `truffle test`

To test the basic tests


## Client Side

### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

# NOTE
you will need metamask extention on your browser, and the ganache account linked to the metamask accounts.
