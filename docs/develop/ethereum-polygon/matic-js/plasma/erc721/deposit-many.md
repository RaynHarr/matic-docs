---
id: deposit-many
title: deplasmaitMany
keywords: 
- 'plasma client, erc721, deplasmaitMany, polygon, sdk'
description: 'Deposit multiple tokens from ethereum to polygon chain.'
---

`deplasmaitMany` method can be used to deposit multiple tokens from ethereum to polygon chain.

```
const erc721RootToken = plasmaClient.erc721(<root token address>, true);

const result = await erc721RootToken.deplasmaitMany([<token id1>,<token id2>], <user address>);

const txHash = await result.getTransactionHash();

const txReceipt = await result.getReceipt();

```
