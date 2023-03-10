<a name="readme-top"></a>
<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
![Contributors][contributors-shield]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="images/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Web3 AIO Documentation</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Preview][preview-gif]

Web3AIO is an application that allows users to interact with smart contracts on the Ethereum blockchain. It has multi-wallet support, real-time contract monitoring with a 0.1 response time, proxy usage, and webhook access, making it easy and efficient for users to manage their contracts.

Why we made it:
* In late 2021, the crypto-currency market exploded with many ways of increasing your wealth, one being NFTs or non-fungible tokens. There were exclusive NFTs with limited supply that if you were able to get your hands on them, you could sell for 10-100x your initial investment. 
* Getting your hands on these products were very difficult since you were competing with tens of thousands of other people trying to make a profit for themselves. Since the demand was so high compared to the supply, the owners of the NFT collections would only allow purchasing at a random time which is how we thought of creating Web3 AIO.
* Instead of having to sit at your computer for hours refreshing their website in hopes we had a chance at purchasing, we created an app that would do it for us. 

Web3 AIO would allow us at a press of a button to monitor these contracts for the sale to go live and instantly purchase NFTs as soon as they were available for the public. A few notable purchases made below with Web3 AIO.

* Purchased 10 GalacticApes at 0.08 ETH ($490.27 USD Value) each

  * Sold for 1.2 ETH ($3512.28 USD Value) each

  * Total Profit 11.2 ETH ($30,220.10 USD Value)

* Purchased 3 SwampVerse at 0.06 ETH ($246.02 USD Value) each

  * Sold for 0.35 ETH ($1468.00 USD Value) each

  * Total Profit 0.87 ETH ($3,665.95 USD Value)



<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Node][Node.js]][Node-url]
* ![Html5][Html5]
* ![CSS][CSS]
* [![Alchemy][Alchemy]][Alchemy-url]
* [![Electron][Electron.js]][Electron-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- DASHBOARD-->
## Dashboard
![Product Name Screen Shot][product-screenshot]

### Features

* Prices Overview
  * Real-time price monitoring of Ethereum and Solana with custom graph interface
  * Real-time gas price monitoring of the Ethereum blockchain with predicted transaction speed
* Your Mints
  * Scrape your default wallet address and display your most recent NFT purchases 

<!-- Tasks-->
## Tasks
![Tasks Screenshot][task-screenshot]
![Tasks Settings Screenshot][tasksettings-screenshot]

### Features

* Create Tasks
  * Opens a pop-up window with customizable settings for the user to input
    * Wallet - Choose designated wallet you would like to use with the specific task
    * Transaction Cost - Cost of one NFT to mint
    * Transaction Quantitity - Total amount of NFTs you would like to mint
    * Contract Address - The address which you will be interacting with
    * Function Name - Name of the function on the contract address you would like to interact with
    * Function Params - Parameters required by the minting function from the contract address
    * Gas Price Method
      * Rapid - Highest gas price for a transaction to be mined (30s - 1min)
      * Medium - Average gas price for a transaction to be mined (5m - 10m)
      * Slow - Lowest gas price for a transaction to be mined (30min - 1hr)
      * Custom - Value set by user
* Start
  * Starts all available tasks simulataneously
* Stop
  * Stops all running tasks simulataneously
* Delete
  * Deletes all available tasks simulataneously
* Speed Up
  * Will resubmit all running tasks with new gas price for a better chance at getting picked up quicker by miners on the blockchain

<!-- Wallets-->
## Wallets
![Wallets Screenshot][wallets-screenshot]

### Features
 * Ability to add unlimited wallet addresses to use for your tasks
 * View Ethereum balance of each wallet

<!-- Proxies-->
## Proxies
![Proxy Screenshot][proxy-screenshot]

To bypass rate-limiting restrictions established by API usage, proxy-usage is required if running multiple tasks.

### Features
 * Copy and paste unlimited proxies with username/password authentication or IP authentication
 * Format (IP:Port:Username:Password) or (IP:Port)

<!-- Settings-->
## Settings
![Settings Screenshot][settings-screenshot]
![Webhook Screenshot][webhook-screenshot]

### Features
 * Discord Wwebhook - Allows users to have their successful and failed transactions to be posted into their discord server
 * API URL - User's Alchemy API url to interact with the Ethereum blockchain
 * Currency - Ability to switch between major worldwide currencies
 * Open task in browser - Will open the transaction hash on https://etherscan.io/ of failed or successful transacstion


<!-- CONTRIBUTING -->
## Contributions

Frontend - https://github.com/callum411/

Backend - https://github.com/parrishstefan/

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Personal Website - https://www.stefanparrish.com/

LinkedIn - https://www.linkedin.com/in/stefan-parrish-875522137/

Github: https://github.com/parrishstefan/

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[preview-gif]: images/preview.gif
[product-screenshot]: images/screenshot.png
[task-screenshot]: images/screenshot2.png
[wallets-screenshot]: images/screenshot3.png
[proxy-screenshot]: images/screenshot4.png
[settings-screenshot]: images/screenshot5.png
[tasksettings-screenshot]: images/screenshot6.png
[webhook-screenshot]: images/webhook.PNG

[contributors-shield]: https://img.shields.io/badge/CONTRIBUTORS-2-brightgreen?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/stefan-parrish-875522137/
[Node.js]: https://img.shields.io/badge/node.js-fffffff?style=for-the-badge&logo=nodedotjs&logoColor=black
[Node-url]: https://nodejs.org/en/
[Html5]: https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=black
[CSS]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=#1572B6
[Alchemy]: https://img.shields.io/badge/alchemy-363FF9?style=for-the-badge&logo=alchemy&logoColor=black&textColor=black
[Alchemy-url]: https://www.alchemy.com/
[Electron.js]: https://img.shields.io/badge/electron-47848F?style=for-the-badge&logo=electron&logoColor=black&textColor=black
[Electron-url]: https://www.electronjs.org/