---
id: did-comm.didcomm.sendmessagedidcommalpha1
title: DIDComm.sendMessageDIDCommAlpha1() method
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DIDComm.sendMessageDIDCommAlpha1() method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

<b>Signature:</b>

```typescript
sendMessageDIDCommAlpha1(args: ISendMessageDIDCommAlpha1Args, context: IAgentContext<IDIDManager & IKeyManager & IResolver & IMessageHandler>): Promise<IMessage>;
```

## Parameters

| Parameter | Type                                                                                                                                                                                                                               | Description                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| args      | [ISendMessageDIDCommAlpha1Args](./did-comm.isendmessagedidcommalpha1args.md)                                                                                                                                                       | Arguments necessary for sending a DIDComm message                                            |
| context   | [IAgentContext](./core.iagentcontext.md) &lt;[IDIDManager](./core.ididmanager.md) &amp; [IKeyManager](./core.ikeymanager.md) &amp; [IResolver](./core.iresolver.md) &amp; [IMessageHandler](./core.imessagehandler.md)<!-- -->&gt; | This reserved param is automatically added and handled by the framework, \*do not override\* |

<b>Returns:</b>

Promise&lt;[IMessage](./core.imessage.md) &gt;

## Remarks

Be advised that this spec is still not final and that this protocol may need to change.
