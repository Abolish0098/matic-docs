---
id: is-exited
title: isExited
keywords: 
- 'plasma client, erc721, isExited, polygon, sdk'
description: 'Checks if a withdraw has been exited.'
---

`isExited` method check if a withdraw has been exited. It returns boolean value.

```
const erc721Token = plasmaClient.erc721(<token address>);

const result = await erc721Token.isExited(<exit tx hash>);

```
