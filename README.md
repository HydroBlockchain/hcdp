# Welcome to the Hydro Community Development Program!

The HCDP is a **core program** to Project Hydro. It is a collection of paid developer bounties **run by the Hydro Community** to advance the ecosystem or its products. Any community member can post and create a task for others to fulfill. These tasks could be for an SDK or library, dApps (Solidity), tutorials, enhancements and more. Tasks get assigned a bounty total and are paid upon fulfilling the requirements.


# List of Completed Hydro Tasks:

The following is a list of tasks **successfully completed** as part of the HCDP by our growing developer community to advance the Hydro ecosystem. Developers can utilize these plugins, smart contracts and code in their development to jump start their project or leverage advanced functionality without re-inventing the wheel.


## Hydro Smart Contracts:

* **[Random Lottery Dynamics](https://github.com/merlox/hydro-lottery):** An Ethereum smart contract uses Hydro Snowflake Ids (EINs) for creating unique lotteries with rewards setup in HYDRO tokens instead of ETH. It's made of an HydroEscrow contract that holds HYDRO for each unique lottery, a Randomizer contract that generates random numbers with Oracles for creating unique, secure randomized numbers for selecting winners and a HydroLottery contract that takes care of the main logic.

  * **Task Reference:** [Issue #256](https://github.com/HydroBlockchain/hcdp/issues/256).
  *  **Developer Bounty:** 4,000,000 Hydro
  * **Author:** [@merlox](https://github.com/merlox)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/merlox/hydro-lottery)
  
* **[Hydro Glacier](https://github.com/ricktobacco/hydro-glacier):** An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

  * **Task Reference:** [Issue #264](https://github.com/HydroBlockchain/hcdp/issues/264).
  *  **Developer Bounty:** 4,000,000 Hydro
  * **Author:** [@ricktobacco](https://github.com/ricktobacco)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/ricktobacco/hydro-glacier)

* **[Hydro Gift Cards](https://github.com/kdmukai/hydro-gift-card):** An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

  * **Task Reference:** [Issue #264](https://github.com/HydroBlockchain/hcdp/issues/264).
  *  **Developer Bounty:** 4,000,000 Hydro
  * **Author:** [@kdmukai](https://github.com/kdmukai)
  * **Deliverable:** [Solidity Smart Contract](https://github.com/kdmukai/hydro-gift-card)


## 3rd Party Hydro Plugins:


* **[Raindrop Client - Wordpress Plugin](https://wordpress.org/plugins/wp-hydro-raindrop/):** Hydro Multi Factor Authentication Plugin (MFA) for Wordpress adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #202](https://github.com/hydrogen-dev/hcdp/issues/202), [Issue #223](https://github.com/hydrogen-dev/hcdp/issues/223), and [Issue #230](https://github.com/hydrogen-dev/hcdp/issues/230).
  * **Developer Bounty:** 500,000 Hydro
  * **Author:** [@adrenth](https://github.com/adrenth)
  * **Deliverable:** [Wordpress Plugin](https://wordpress.org/plugins/wp-hydro-raindrop/)
 
* **[Raindrop Client - Joomla Plugin](https://github.com/DaveM2011/joomla-hydro-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for Joomla adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #219](https://github.com/hydrogen-dev/hcdp/issues/219).
  * **Developer Bounty:** 700,000 Hydro
  * **Author:** [@DaveM2011](https://github.com/DaveM2011) 
  * **Deliverable:** [Joomla Plugin](https://github.com/DaveM2011/joomla-hydro-raindrop)

* **[Raindrop Client - Passport.js Module](https://github.com/Red-Maximus/passport-raindrop):** Hydro Multi Factor Authentication Plugin (MFA) for Passport.js adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.
  * **Task Reference:** [Issue #211](https://github.com/hydrogen-dev/hcdp/issues/211).
  * **Developer Bounty:** 500,000 Hydro
  * **Author:** [@Red-Maximus](https://github.com/Red-Maximus) 
  * **Deliverable:** [Passport.js Module](https://github.com/Red-Maximus/passport-raindrop)

 


## Hydro SDKs:

* **[Hydro Raindrop SDK for PHP](https://github.com/adrenth/raindrop-sdk):** This PHP library provides a suite of convenience functions intended to simplify the integration of Hydro's [Raindrop authentication](https://www.hydrogenplatform.com/hydro) into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #208](https://github.com/HydroBlockchain/hcdp/issues/208).
  *  **Developer Bounty:** 200,000 Hydro ([txn](https://etherscan.io/tx/0xd49252811742613ccc2222595b2b3a813bc3d4e181409210004f2f09084528b5))
  * **Author:** [@adrenth](https://github.com/adrenth)
  * **Deliverable:** [SDK](https://github.com/adrenth/raindrop-sdk)


* **[Hydro Raindrop SDK for Java](https://github.com/serkanalgl/hydro-raindrop-java):** This Java library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #209](https://github.com/HydroBlockchain/hcdp/issues/209).
  *  **Developer Bounty:** 200,000 Hydro ([txn](https://etherscan.io/tx/0x2e69a09b8336da41a1745e84e077f68e5226a8b4749e5298cef182ecdb3517af))
  * **Author:** [@serkanalgl](https://github.com/serkanalgl)
  * **Deliverable:** [SDK](https://github.com/serkanalgl/hydro-raindrop-java)
  
* **[Hydro Raindrop SDK for ColdFusion](https://github.com/brett91ag/coldfusion-hydro-raindrop):** This ColdFusion library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the [Raindrop documentation](https://www.hydrogenplatform.com/docs/hydro/v1/#Raindrop).

  * **Task Reference:** [Issue #212](https://github.com/HydroBlockchain/hcdp/issues/212).
  *  **Developer Bounty:** 25,000 Hydro ([txn](https://etherscan.io/tx/0xffbe769a502b677b42c1d2483507ed9647843ca05a6dcfb1fd836f3320ee6916))
  * **Author:** [@brett91ag](https://github.com/brett91ag)
  * **Deliverable:** [SDK](https://github.com/brett91ag/coldfusion-hydro-raindrop)

## Hydro Code Audits:

1. Hydro DA Smart Contract. Reference: [Issue #218](https://github.com/hydrogen-dev/hcdp/issues/218).
