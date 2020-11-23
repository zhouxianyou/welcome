---
content_title: Software Manuals
link_text: Software Manuals
---

# Manuals (Component Guides)
Click on the following links to find detailed documentation for each component.

## Core Components
The main components of the EOSIO platform.
* [nodeos](https://developers.eos.io/manuals/eos/latest/nodeos/index) : The core service daemon that runs on every EOSIO node.
* [cleos](https://developers.eos.io/manuals/eos/latest/cleos/index) : A command line interface to interact with the blockchain and manage wallets.
* [keosd](https://developers.eos.io/manuals/eos/latest/keosd/index) : A key manager service daemon for storing private keys and signing digital messages.
* [eosio.cdt](https://developers.eos.io/manuals/eosio.cdt/latest/index) : Contract Development Toolkit is a suite of tools used to build EOSIO contracts.
* [eosio.contracts](https://developers.eos.io/manuals/eosio.contracts/latest/index) : Smart contracts that provide some of the basic functions of the EOSIO blockchain.
* [eos-vm](https://github.com/EOSIO/eos-vm) : EOS VM - A Low-Latency, High Performance and Extensible WebAssembly Engine.
        
## Tools
Tools to help you use the EOSIO platform.
* [eosio-explorer](https://github.com/EOSIO/eosio-explorer) : An application providing Web GUI to communicate with EOSIO blockchain in a local development environment.
* [eosio-toppings](https://github.com/EOSIO/eosio-toppings) : A monorepo composed of the various packages which work together to create a web-based development tool to help users create applications on the EOSIO blockchain.
* [eosio-web-ide](https://github.com/EOSIO/eosio-web-ide) : EOSIO Quickstart Web IDE lets developers start experiment building applications on EOSIO platform in a matter of minutes.
* [demux-js](https://github.com/EOSIO/demux-js) : Demux is a backend infrastructure pattern for sourcing blockchain events to deterministically update queryable datastores and trigger side effects.
* [history-tools](https://developers.eos.io/welcome/latest/tools/history-tools/index) : Set of tools built to facilitate highly performant searches, written in C++, that can efficiently and scalably sift through terabytes of data from the full history of EOSIO blockchains.
        
## Javascript SDK
Connect to the EOSIO platform in javascript.
* [eosjs](https://developers.eos.io/manuals/eosjs/latest/index) : A Javascript library which provides an API for integrating with EOSIO-based blockchains using the EOSIO Nodeos RPC API.
* [eosjs-keygen](https://github.com/EOSIO/eosjs-keygen) : A Javascript library for managing keys in local storage.
        
## Swift SDK
Connect to the EOSIO platform in Swift.
### eosio-swift
An API for integrating with EOSIO-based blockchains using the EOSIO RPC API
* [API documentation](https://eosio.github.io/eosio-swift)
* [Git](https://github.com/EOSIO/eosio-swift)
### eosio-swift-vault
Consists of two main components--Vault and Vault Signature Provider. Vault is a utility library for working with public/private keys and signing with Apple's Keychain and Secure Enclave. Vault Signature Provider is a pluggable signature provider for EOSIO SDK for Swift. It allows for signing transactions using keys stored in Keychain or the device's Secure Enclave.
* [API documentation](https://eosio.github.io/eosio-swift-vault) 
* [Git](https://github.com/EOSIO/eosio-swift-vault) 
### eosio-swift-ios-example-app:
A simple application demonstrating how to integrate an iOS app with EOSIO-based blockchains using EOSIO SDK for Swift
* [Git](https://github.com/EOSIO/eosio-swift-ios-example-app)

## Java SDK
Connect to the EOSIO platform in java.
### eosio-java
An API for integrating with EOSIO-based blockchains using the EOSIO RPC API
* [API documentation](https://eosio.github.io/eosio-java) 
* [Git](https://github.com/EOSIO/eosio-java) 
### eosio-java-rpc-provider
An RPC provider implementation for use within EOSIO SDK for Java as a plugin. Supports Android 6+ and server-side Java.
* [Git](https://github.com/EOSIO/eosio-java-rpc-provider) 
### eosio-java-abieos-serialization-provider
A pluggable serialization provider for EOSIO SDK for Java supporting server-side Java
* [Git](https://github.com/EOSIO/eosio-java-abieos-serialization-provider) 
### eosio-java-android-abieos-serialization-provider
A pluggable serialization provider for EOSIO SDK for Java supporting Android
* [API documentation](https://eosio.github.io/eosio-java-android-abieos-serialization-provider) 
* [Git](https://github.com/EOSIO/eosio-java-android-abieos-serialization-provider) 
### eosio-java-softkey-signature-provider
An example pluggable signature provider for EOSIO SDK for Java
* [API documentation](https://eosio.github.io/eosio-java-softkey-signature-provider) 
* [Git](https://github.com/EOSIO/eosio-java-softkey-signature-provider) 
### eosio-android-keystore-signature-provider
A pluggable signature provider for EOSIO SDK for Java written in Kotlin supporting Android
* [API documentation](https://eosio.github.io/eosio-android-keystore-signature-provider) 
* [Git](https://github.com/EOSIO/eosio-android-keystore-signature-provider) 
### eosio-java-android-example-app
A simple application demonstrating how to integrate an Android app with EOSIO-based blockchains using EOSIO SDK for Java
* [Git](https://github.com/EOSIO/eosio-java-android-example-app) 


## EOSIO Labs
Libraries to connect and authenticate blockchain transactions.
* [eosjs-ios-browser-signature-provider-interface](https://github.com/EOSIO/eosjs-ios-browser-signature-provider-interface) : A Signature Provider Interface for communicating with an authenticator from iOS Safari using the EOSIO Authentication Transport Protocol Specification.
* [eosjs-ledger-signature-provider](https://github.com/EOSIO/eosjs-ledger-signature-provider) : A SignatureProvider for communicating with eosjs from a Ledger device.
* [eosjs-signature-provider-interface](https://github.com/EOSIO/eosjs-signature-provider-interface) : An abstract class that implements the EOSJS Signature Provider interface, and provides helper methods for interacting with an authenticator using the EOSIO Authentication Transport Protocol Specification.
* [eosjs-window-message-signature-provider-interface](https://github.com/EOSIO/eosjs-window-message-signature-provider-interface) : A Signature Provider Interface for communicating with an authenticator over the Window Messaging API using the EOSIO Authentication Transport Protocol Specification.
* [ual-authenticator-walkthrough](https://github.com/EOSIO/ual-authenticator-walkthrough) : A tutorial walks through the steps required to create a UAL for Ledger Authenticator.
* [ual-reactjs-renderer](https://github.com/EOSIO/ual-reactjs-renderer) : A library provides a React renderer around the Universal Authenticator Library.       

## Examples
Sample applications.
* [eosio-java-android-example-app](https://github.com/EOSIO/eosio-java-android-example-app) : Application demonstrating integration with EOSIO-based blockchains using EOSIO SDK for Java
* [eosio-swift-ios-example-app](https://github.com/EOSIO/eosio-swift-ios-example-app) : Application demonstrating integration with EOSIO-based blockchains using EOSIO SDK for Swift
* [tropical-example-web-app](https://github.com/EOSIO/tropical-example-web-app) : An example for developers showing an application built on EOSIO combining UAL, Manifest Spec, and Ricardian Contracts