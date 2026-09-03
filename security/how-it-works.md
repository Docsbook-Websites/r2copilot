---
title: "How R2 Copilot keeps your content private"
description: "R2 Copilot encrypts prompts on your device, moves them through the patented SDNP network where packets are split, mixed and re-encrypted across independent nodes, and discards content when the add-in closes."
---

# How R2 Copilot keeps content private

R2 Copilot protects content in three places at once: **on your device**, where prompts are encrypted before they leave; **in transit**, where the patented SDNP protocol splits, mixes and repeatedly re-encrypts packets across independent nodes; and **at the end of the session**, where content is discarded when you close the add-in. Nothing you type is retained to improve a model.

## On your device

Content you compose and prompts you enter while working with R2 Copilot are encrypted on your device. The encryption happens before the text is sent, so the plain text of your message never travels the public internet.

## In transit: SDNP

Transport is handled by the **Secure Dynamic Communication Network and Protocol (SDNP)**, a patented data-transfer technology designed to secure data in transfer, in use and at rest.

SDNP relies on multi-route, meshed communications to route data packets dynamically. Inside the network, packets are:

- **scrambled** — reordered so their sequence carries no meaning,
- **split** — divided so no single node holds a whole message,
- **mixed** — combined with other traffic,
- **repeatedly encrypted and decrypted** as they pass through independent media nodes in the cloud.

Because security operations are integrated into routing rather than layered on top of it, an observer at any single node sees fragments of reordered, encrypted traffic instead of a conversation.

## The last mile

The leg between the SDNP media nodes and the end-user device is covered separately by patented **Last Mile Protection** technology. This is the segment where an otherwise well-protected message is usually most exposed, which is why it is handled as its own layer rather than as part of general transport.

## At the end of the session

When you close the add-in, the content you composed and the prompts you entered are immediately deleted. The assistant does not store chat history. That is why R2 does not ask you to clear a conversation log — there is not one.

## What this means in practice

- **Your text is not training material.** R2 does not store, collect or share user-generated content, so it cannot be used to improve a model.
- **A leak of a shared conversation is not possible if there is no shared conversation.** The recurring incident pattern collected on the vendor's [Leaks Radar](https://r2copilot.ai/leaks-radar) — chat links indexed by search engines, share features exposing medical and financial documents — depends on stored, shareable chats.
- **Compliance follows from the design, not from a promise.** Encryption in transit and at rest is what the regulatory claims rest on; see [Compliance and certification](./compliance.md).

## Next

- [What is stored and what is not](./data-handling.md) — the concrete list for a security review.
- [Compliance and certification](./compliance.md) — GDPR, HIPAA, CCPA and the Microsoft certification.
