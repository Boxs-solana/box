---
description: Adoption of ERC115 protocol
---

# ERC1155+SPL20

What is ERC-1155 A standard contract interface that can manage multiple tokens. Only one contract can be deployed to issue and manage any variety of homogeneous, non-fungible, or semi-fungible tokens. The official summary is: “A standard interface for managing contracts of multiple token types. A single deployed contract can include any combination of fungible tokens, non-fungible tokens, or other configurations (such as semi-fungible tokens).”

## Inspiration from ERC1155

What kind of sparks will emerge when ERC115+SPL20 collides, semi-homogeneity + MINT, strong community consensus, and a huge user base.

## One smart contract, multiple tokens

Currently, the BRC-20 and ERC-721 standards require the deployment of a new contract each time a token is issued, while the core concept hidden behind the ERC-1155 standard is that a single smart contract can manage unlimited types of tokens. Consider an automatic shopping machine with sodas, juices and snacks. Consumers interact with the machine through a single secure interface (inject a coin, press a button). Machines deliver goods based on consumer choices. Similarly, an ERC-1155 standard game contract can be composed of a large number of items or components, representing everything from weapons to armor to health values, magic values, etc. All of these items or components are repeatable and you can get more than one. Repeatable tokens are often used as divisible currencies (most SPL-20 tokens). Repeatable tokens are very useful for stackable items (they do not need to be differentiated), such as a barrel of arrows for a certain bow. Another type of token is called non-repeatable tokens (NFTs). This structure allows each token to have its own unique parameters, history, and mapping to the real world. A pet dragon in a video game could be an NFT, with its own unique name, level, and history within the game. ​
