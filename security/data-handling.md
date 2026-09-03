---
title: "What R2 Copilot stores and what it does not"
description: "R2 Copilot does not store chat history or user-generated content. What the service does hold, which Azure services it runs on, what access controls apply, and how to delete your data and account."
---

# What is stored and what is not

**R2 Copilot does not store, collect or share user-generated content, and the assistant does not keep chat history.** Prompts and composed content are encrypted on your device and deleted when you close the add-in. What remains is the account and subscription information needed to run the service, and you can delete that at any time.

This page exists to be sent to a security reviewer, so it states the negative claims as plainly as the positive ones.

## Not stored

| Item | Status |
|---|---|
| Prompts you type | Encrypted on device, discarded when the add-in closes |
| Assistant replies | Not retained as chat history |
| Document or email content passed to the assistant | Not stored, collected or shared |
| Your content as training data | Not used to train or improve a model |

## Where the service runs

R2 Copilot runs inside Microsoft's cloud. The platform is engineered to the Azure Well-Architected Framework and maintains "Moderate" or higher scores across Reliability, Security and Operational Excellence. It uses:

- **Azure Blob Storage** — with encryption at rest,
- **Azure SQL Database**,
- **Azure Key Vault** — for key management.

## Access controls

- **End-to-end protection.** All communication uses HTTPS encryption; data at rest is encrypted within Azure Blob Storage.
- **Access governance.** Role-based access control and private endpoints restrict permissions to verified internal components.
- **User data control.** Customers can delete their data and their accounts at any time.

## What the add-in can access while you use it

The Outlook add-in can read and modify the contents of items in your mailbox and create new ones. That includes the body, subject, sender, recipients and attachments of the message you have open — which is what a drafting assistant needs to draft. The access is what the add-in is granted; what happens to the content afterwards is covered above.

## Deleting your data

You can delete your data and your account at any time. Because chat history is not retained, deletion covers account and subscription records rather than a conversation archive.

To request deletion, or written confirmation of it for an audit file, use the [contact form](https://r2copilot.ai/contacts) and say which account and which records you mean. [What to include](../support.md).

## Questions a reviewer usually asks next

- **Which sub-processors are involved?** Ask through the [contact form](https://r2copilot.ai/contacts) — the answer depends on your deployment and region.
- **Where is data processed geographically?** Same route; the platform runs in Azure, and the region applicable to your tenant is confirmed on request.
- **Is there a data processing agreement?** Request it with your company details; see [Compliance and certification](./compliance.md).

## Next

- [How R2 keeps content private](./how-it-works.md) — the mechanism behind these claims.
- [Compliance and certification](./compliance.md) — the regulations named and the Microsoft certification held.
