---
id: filecoin.js.jsonrpcprovider.statereplay
title: JsonRpcProvider.stateReplay() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[filecoin.js](./filecoin.js.md) &gt; [JsonRpcProvider](./filecoin.js.jsonrpcprovider.md) &gt; [stateReplay](./filecoin.js.jsonrpcprovider.statereplay.md)

## JsonRpcProvider.stateReplay() method

returns the result of executing the indicated message, assuming it was executed in the indicated tipset

<b>Signature:</b>

```typescript
stateReplay(tipSetKey: TipSetKey, cid: Cid): Promise<InvocResult>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  tipSetKey | TipSetKey |  |
|  cid | Cid |  |

<b>Returns:</b>

Promise&lt;InvocResult&gt;