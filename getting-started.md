---
title: "Install R2 Copilot and run your first prompt"
description: "Install the R2 Copilot add-in from the Microsoft store, approve it, open the assistant panel and send your first prompt. Covers the free trial and what to do when the panel does not appear."
---

# Install R2 Copilot and run your first prompt

Installing R2 Copilot takes three steps: get the add-in from the Microsoft store listing for your app, approve it once inside the app, and open the assistant panel. There is a free trial, so you can do this before any purchase decision.

## Before you start

- One of the supported apps: Outlook, Word, Excel, PowerPoint or OneNote. See [Supported apps](./availability.md) for which listing covers which app.
- Permission to install an add-in. In a managed tenant an administrator may need to approve it for your organisation.
- A few minutes. Nothing has to be configured before the first prompt.

<!-- widget:stepper -->

### Open the store listing for your app

Each app has its own listing in the Microsoft marketplace, published under **Stealth Mail** — the company behind R2 Copilot:

- Outlook — listing `WA200005943`
- Word, OneNote and PowerPoint — listing `WA200006000`
- Excel — listing `WA200006007`

Press **Get it now** on the listing. If you are installing for a team rather than yourself, hand these identifiers to whoever administers your Microsoft 365 tenant; they are what the admin center asks for.

### Install and run the add-in

Follow the store flow to install, then open the app. The add-in appears on the ribbon of the app you installed it into.

### Approve the add-in

Click **Get Started** and approve the use of the add-in. The add-in asks for the access it needs to read the item you are working on and write the reply it drafts — in Outlook, that means the body, subject, sender, recipients and attachments of the message you have open.

### Open the assistant panel

On the main panel, click the **[...]** icon to open R2 Copilot. The panel opens beside your document or message; you keep working in the app itself.

### Send your first prompt

Type what you want in plain language: *summarise this thread in three sentences*, *reply politely and ask for the invoice*, *explain what changed between these two columns*. The assistant answers in the panel, and you decide what goes into the document.

<!-- /widget -->

## Rolling it out to a team

An administrator can deploy the add-in centrally instead of asking each person to install it, using the listing identifiers above. Two things are worth agreeing before the rollout: who is on the subscription, since prompts and tokens come out of one shared pool ([Plans and pricing](./pricing.md)), and what your security review needs, which is answered on [What is stored and what is not](./security/data-handling.md).

## The free trial

R2 Copilot is free to try before you subscribe. On the main page of the website, under **Try for Free**, select the application you want to activate the free version for. At the end of the trial period you need a subscription to keep using the assistant — see [Plans and pricing](./pricing.md).

## When you close the add-in

Closing the add-in ends the session. Content you composed and prompts you entered are discarded at that point, and no chat history is kept. This is the intended behaviour, not a timeout: if you need a draft, copy it into your document before you close the panel.

## If the panel does not appear

- Check that the add-in is enabled in the app's add-in list; a managed tenant can block add-ins by policy.
- Check you installed the listing that covers your app — the Word listing also covers OneNote and PowerPoint, but Outlook and Excel have their own.
- Still stuck: send the app name, its version and what you see instead of the panel to the [contact form](https://r2copilot.ai/contacts). [What to include](./support.md).

## Next

- [Plans and pricing](./pricing.md) — what to pick when the trial ends.
- [What is stored and what is not](./security/data-handling.md) — the question your security team will ask first.
- [Outlook](./apps/outlook.md), [Word](./apps/word.md), [Excel](./apps/excel.md) — what the assistant does in each app.
