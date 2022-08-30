<!-- Creds to https://github.com/othneildrew/Best-README-Template -->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="./images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Documentation</h3>

  <p align="center">
    Bringing Twitter to Lukso with ChainLink Oracle Services
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>View Demo »</strong></a>

  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->
Twitter Name Space (TNS) is using ChainLink Oracle Request to verify your Twitter ID.

<!-- GETTING STARTED -->
## Getting Started

The website is divided into two parts:

The ChainLink Faucet where any user can claim LINK from the faucet at every __12 hour__ intervals. This is a mitigation used to prevent spam atacks and prevent bad actors from draining the pool.

The Twitter Name Space where any user can __connect__ their Twitter ID to their wallet address, __update__ / __resolve__ their existing wallet address to a different twitter ID, and __search__ a user's twitter ID to see their connected wallet.

## Guide (Step-by-step)
The website can be daunting at first for inexperienced tech users. As a result, we have currated this guide to ease the process of registering you TNS!
If you're using a UP, start at step 3; otherwise, start at step 1.

1. First and foremost, you must have L16 LYXE test-net tokens. These will be used for gas. You can acquire these [here](https://faucet.l16.lukso.network/).

2. Head over to the [LINK page](https://luksoracle.github.io/frontend/faucet.html) where you will request for `20 LINK`. If the faucet is empty, you will need to patiently wait for it to top-up. Please be mindful, you can only request every 12 hours.

3. Retrieve your [Twitter ID](https://tweeterid.com/) by entering your twitter username (e.g. @rickastley = 148137271).

4. Go to the [TNS page](https://luksoracle.github.io/frontend/twitter.html), connect your wallet, and insert your retrieved Twitter ID in the text-field, and hit the `Register` button. 

__NOTE:__ Notice that, in the TNS page, the `Twitter LINK Balance` in the modal above the text-fields shows the amount of LINK in the twitter contract. If the LINK balance is larger than 0 LINK, you should be okay to proceed. Otherwise, the modal will display an address you will need to send LINK to (from Step 2) with a wallet before being able to register your twitter account.

5. Once you have registered and you have confirmed the transctions through MetaMask, you should be able to insert your Twitter ID into the text-field and see the wallet address linked to it but hitting the `Enter` button.

6. _OPTIONAL:_ If you ever need to change the address your Twitter ID points to, you can do so by using the `Resolve` button on screen.

<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are welcome!

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Clone the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

smart contracts: [Marcus Wentz](https://twitter.com/goerlibot) <br>
devops+js: [@0x_rxx](https://twitter.com/0x_rxx) <br>
frontend: [@0xfinesto](https://twitter.com/0xfinesto) <br>
logo: [@gabibibah](https://twitter.com/gabibibah) <br>
advisor(s): [@johannafransn](https://github.com/johannafransn)
