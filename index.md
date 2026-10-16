---
layout: default
title: Privacy Policy
---

# CompanionLink Privacy Policy

Last updated: October 15, 2026.

CompanionLink is a Chrome extension that exports your own AI companion chat
history, for dates you choose, to a CSV file on your computer. It supports Replika
and Kindroid. It connects only to the app you export from and does not send your
data to its developers or to anyone else.

## Data the extension handles

- **Chat messages** and their details: timestamps, sender, message IDs, and, for
  Replika, reactions. For Kindroid, the extension also shows your Kin's name after an
  export.
- **Replika**: the login session your browser already uses for Replika (an
  authentication token and account and device identifiers). CompanionLink never asks
  for your password.
- **Kindroid**: the Kindroid API key you paste into the extension, and the chat ID in
  the address of the chat you have open.
- **What you enter**: your participant ID and dates, and your computer's time zone.
- **The current tab's address**: when you open the extension, it reads the address
  only to tell whether the tab is a Replika page or a Kindroid chat. The address is
  not stored or sent.

## How it is used

- **Replika**: each time a Replika page loads, even if you never open the extension,
  the extension reads that page's login-session information from the page's storage
  and from the session message the page sends to Replika. When you click Export, it
  uses that session to request your chat history directly from Replika over an
  encrypted connection.
- **Kindroid**: when you click Export, the extension sends your API key, the chat's ID
  and the start of your date range to Kindroid's official API over an encrypted
  connection, to request that chat's history.
- The extension keeps only messages within your selected dates and creates the CSV
  on your computer. Your participant ID is used only as the file name.

## Sharing and Limited Use

The extension connects only to Replika or Kindroid, to request your own history. It
does not upload, sell or share your data, and it has no advertising or analytics.
Its use of your data complies with the Chrome Web Store User Data Policy, including
the Limited Use requirements.

Sharing the downloaded file with anyone, including researchers, is your choice and
happens outside the extension.

## Storage

- Nothing is saved to extension storage. Session information, your API key and
  messages are held only in browser memory.
- Replika: the session can stay in memory until the Replika page is closed or
  reloaded; finishing an export does not clear it.
- Kindroid: your API key is cleared from the form when the export ends or the
  extension window closes. Kindroid's replies are requested so that Chrome does not
  keep them in its cache.
- The CSV stays on your computer until you delete it. It is not encrypted and
  contains your conversation text.
- CompanionLink does not control what Replika's or Kindroid's own websites keep in
  your browser.

## Your choices

You decide when to export and for which dates. Disable or uninstall the extension to
stop it. Uninstalling does not delete files you have already downloaded. Your
Kindroid API key gives full access to your Kindroid account; you can regenerate it in
Kindroid's settings at any time, which stops the old key from working.

## Changes and contact

This policy will be updated if these practices change. Questions:
[gospark@syr.edu](mailto:gospark@syr.edu).
