---
title: "R2 Copilot compared with public AI chatbots"
description: "Point-by-point comparison of R2 Copilot and general-purpose AI chatbots on data retention, training use, encryption, third-party sharing and regulatory compliance."
---

# R2 Copilot and public AI chatbots

The difference is not what the assistant writes — both use current language models — but what happens to what you type. A public chatbot is built around a stored, shareable conversation. R2 Copilot is built around a conversation that is encrypted on your device and discarded when you close the panel.

## Point by point

| | Typical public AI chatbot | R2 Copilot |
|---|---|---|
| Your content | May be subject to public disclosure | Encrypted on your device, discarded when the add-in closes |
| Data collection | Extensive collection of user-generated information | Does not store, collect or share user-generated content |
| Model training | Content used to improve the model | Content not used for training |
| Encryption of sensitive text | Often none end to end | Encrypted in transit and at rest |
| Third parties | Personal data shared with third-party processors | Communications stay between you and the assistant |
| Regulation | Compliance frequently unresolved | Built to comply with GDPR, HIPAA and CCPA |
| Where you work | A separate window you paste into | A panel inside Outlook, Word, Excel, PowerPoint, OneNote or the browser |

## Why "shareable chat" is the risk to look at

The incidents collected on the vendor's [Leaks Radar](https://r2copilot.ai/leaks-radar) — dated, sourced and archived — repeat one pattern: shared conversation links being indexed by search engines, exposing clinical trial data, resumes, API keys and internal company files. The exposure came from the share feature working as designed, not from a break-in.

An assistant that does not retain chat history has no such link to expose. That is the structural argument, and it is why [what is stored](../security/data-handling.md) is the page to read before the feature list.

## What you give up

Being straight about it saves a disappointed evaluation:

- **No conversation history to return to.** Sessions are not saved. If you want a draft, put it into the document before closing the panel.
- **Usage is metered.** Prompts and tokens come out of a monthly pool rather than being unlimited. [Plans and pricing](../pricing.md).

## Next

- [Choosing between R2 Copilot and a built-in assistant](./built-in-assistants.md).
- [How R2 keeps content private](../security/how-it-works.md).
