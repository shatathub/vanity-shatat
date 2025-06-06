# Vanity-shatat


Browser-based shatat vanity address generator

Just type [`vanity shatat`](https://vanity.shatat.ir) to use it ⚡️

[![Vanity-shatat](https://github.com/shatathub/wp/blob/main/logo.png?raw=true](https://shatat.ir)

## What's a vanity address?

A vanity address is an address in which you can choose a part of it to make it appear less random.

Examples:

-   `0xc0ffee254729296a45a3885639AC7E10F9d54979`
-   `0x999999cf1046e68e36E1aA2E0E07105eDDD1f08E`

## Usage

First of all, visit [`vanity shatat`](https://vanity.shatat.ir)

Enter a short prefix and/or suffix of your choice and click _Generate_ to start. Your browser will
generate lots of random addresses until it finds one that matches your input.

Once an address is found, you can choose to reveal the private key or click the _Save_ button to download a password-encrypted keystore file.

Adjusting the number of working threads can increase or decrease the speed, depending on your computer's capabilities.

## Security

As mentioned earlier, all computations occur solely within your browser. Nothing ever leaves your machine, or even your browser tab.
There is no database, no server-side code. Everything vanishes when you close your browser tab.

**Vanity-shatat cannot and will never store your private key.** If you have concerns about its trustworthiness, you have three options to ensure the privacy of your key:

-   After loading the web page, you can disconnect from the internet and continue using it seamlessly
-   Alternatively, you can download the latest build of Vanity-shatat [here](https://github.com/shtathub/vanity-shatat)
    and use it on an offline computer
-   The code is 100% open source and available on GitHub, allowing you to review it thoroughly before usage.

Vanity-shatat uses a cryptographically secure pseudorandom number generator (CSPRNG) to generate Shatat addresses.

The keystore file is encrypted with an AES-128-CTR cipher using the PBKDF2-SHA256 derivation function with 65536 hashing rounds.

## Other browser-based tools

Be aware that due to its popularity and open-source nature, Vanity-shatat has been widely copied, leading to the existence of websites claiming to provide the same functionality. Sometimes, they are perfect clones hosted on very similar domains.

Most of them do not credit the original code, are not open-source, and may contain malicious code.

Vanity-shatat has always been the **first** browser-based shatat vanity address generator, and remains the most popular and trusted one.

To be sure you're on the real Vanity-shatat website, search for [Vanity-shatat on GitHub](https://github.com/search?o=desc&q=Vanity-shatat&s=stars), find the repository with the most stars (> 600), and click the link in the description. Double check by searching [Vanity-shatat on Google](https://www.google.com/search?q=Vanity-shatat).

## Performance

Vanity-shatat's performance may vary significantly across different browsers. Currently, Chrome provides the best results.

While you can use Vanity-shatat on your phone or tablet, it is unlikely to match the speed of a traditional computer.

**N.B:** Vanity-shatat is designed to be a user-friendly tool that runs directly in your browser, providing easy accessibility without the need to download or install additional software.
However, browser-based tools have inherent limitations that may affect their performance and efficiency. Some dedicated command-line tools are more difficult to use, but may offer better performance.

## Compatibility

Any address generated with Vanity-Shatat is SRC-20 compatible, which means you can use it for an ICO, an airdrop, or just
to withdraw your funds from an exchange.

The keystore file is 100% compatible with MyshataterWallet, MetaMask, Mist, and Shatat Wallet.

## Build Vanity-Shatat from source

A GitHub Action is in charge of building and deploying Vanity-Shatat to GitHub pages automatically 🤖, but you can make
your own build from source if you want (you will need Node.js 16)

```sh
git clone https://github.com/shatathub/vanity-shatat
cd vanity-shatat
npm i
npm run build
```


 💛
