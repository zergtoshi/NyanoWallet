# Nault

![GitHub Pages](https://github.com/Nault/Nault/workflows/GitHub%20Pages/badge.svg)
![Electron App](https://github.com/Nault/Nault/workflows/Electron%20App/badge.svg)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=Nault_Nault&metric=alert_status)](https://sonarcloud.io/dashboard?id=Nault_Nault)
[![GitHub All Releases](https://img.shields.io/github/downloads/nault/nault/total)](https://github.com/Nault/Nault/releases/latest)
[![Discord](https://img.shields.io/badge/discord-join%20chat-orange.svg)](https://discord.nanocenter.org)

Nault is a community driven fork of the popular Nano wallet [NanoVault](https://github.com/cronoh/nanovault) 💙

It's a fully client-side signing wallet for sending and receiving [Nano](https://github.com/nanocurrency/nano-node/) either directly in your browser at [nault.cc](https://nault.cc) or with the [desktop app](https://github.com/Nault/Nault/releases/latest).

Seamless integration with any Nano compatible RPC backend/websocket and the aim to be more frequently maintained are some of the main features. Those together will greatly increase the stability, performance and uptime.

![Nault Screenshot](/src/assets/img/preview.png)
___

## How To Use
Nault comes in different flavors to suit your need.
#### Desktop App
Available for Windows/Mac/Linux - just head over to the [latest release](https://github.com/Nault/Nault/releases/latest) and download the version for your OS:

* Windows: *.exe
* Linux: *.AppImage
* Max: *.dmg

If you want to verify the binary checksum you can download the corresponding checksum file. There are plenty of apps to do this, one way is using a powershell or bash terminal.

* **Powershell:** Get-FileHash -Path '.\Nault Setup x.x.x.exe' -Algorithm SHA512
* **Bash:** openssl sha512 Nault-x.x.x.AppImage

#### Web App
You can also use Nault from any device on the web at [nault.cc](https://nault.cc).

Both the desktop (recommended) and web version supports the Ledger Nano hardware wallet. For help using it, please refer to [this guide](https://docs.nault.cc/2020/08/04/ledger-guide.html).

The web version can additionally be pulled from the [dockerhub repo](https://hub.docker.com/r/nault/nault) using: docker pull nault/nault:latest

A full security guide and other useful articles can be found in the [Nault Docs](https://docs.nault.cc).

## How To Help

Thanks for your interest in contributing! There are many ways to contribute to this project. [Get started here at CONTRIBUTING.md](CONTRIBUTING.md).

If you want to know how to setup the development environment head over to [DEVELOPMENT.md](DEVELOPMENT.md).

## Support

If you are looking for more interactive and quick support compared to creating a new Github issue, you will then find most of the developers in the Nault channel over at the [TNC discord server](https://discord.nanocenter.org/).

## Acknowledgements

Special thanks to the following!

- [NanoVault](https://github.com/cronoh/nanovault) - The original one
- [numtel/nano-webgl-pow](https://github.com/numtel/nano-webgl-pow) - WebGL PoW Implementation
- [jaimehgb/RaiBlocksWebAssemblyPoW](https://github.com/jaimehgb/RaiBlocksWebAssemblyPoW) - CPU PoW Implementation
- [dcposch/blakejs](https://github.com/dcposch/blakejs) - Blake2b Implementation
- [dchest/tweetnacl-js](https://github.com/dchest/tweetnacl-js) - Cryptography Implementation

## Donations

If you have found Nault useful and are feeling generous, you can donate at
`nano_3niceeeyiaa86k58zhaeygxfkuzgffjtwju9ep33z9c8qekmr3iuc95jbqc8`

Thanks a lot!
