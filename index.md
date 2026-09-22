---
layout: default
title: Privacy Policy
---

# Companion Chat Log Export Privacy Policy

Last updated: September 21, 2026.

Companion Chat Log Export is a free Chrome extension provided by LinkLab at
Syracuse University. It lets you download your own Replika chat history for a
date range you select. It does not automatically send your chat log to LinkLab.

## Information The Extension Handles

To provide the export, the extension handles:

- The participant ID you enter, the dates you select and your computer's time zone.
- Chat messages and their metadata, including timestamps, sender, reactions and
  message IDs.
- Replika session authentication information, including authentication tokens and
  account/device identifiers needed to request history using your existing login.

The extension does not ask you to enter your Replika password.

## When And How Information Is Used

On matching Replika pages, the extension reads page storage and observes outgoing
WebSocket initialization messages to locate login-session information. This can
happen when a page loads, before you open the export popup or click Export.
The captured initialization message passes through the page's messaging channel
to the extension's content script.

Chat-history retrieval starts when you submit the export form. Authenticated
requests go directly to Replika over an encrypted WebSocket connection. Returned
history batches may include messages outside your selected dates; filtering and
CSV creation happen locally, and only matching messages are included in the file.

Your participant ID is used to name the downloaded CSV. It is not a request to
create a Replika account or send the file to a researcher.

## Sharing And Limited Use

We use the information handled by this extension only to provide its chat-export
function, consistent with the Chrome Web Store User Data Policy, including its
Limited Use requirements.

The extension has no advertising or tracking analytics. It does not sell data,
use data for advertising, or upload your chat history or authentication information
to LinkLab or a third-party collection service. Replika receives the authenticated
requests necessary to provide your history.

If you participate in a study, submitting the downloaded file to researchers is a
separate action. The study's consent and data-handling instructions govern that
submission and the researchers' subsequent use and retention of the file.

## Storage And Retention

The extension processes session information and export data in browser memory.
It does not write authentication information to persistent extension storage.
The cached session can remain for the lifetime of the Replika page's content-script
context, until replaced or that context is destroyed. Completing an export or
closing the popup does not clear the still-open page's session cache.

The downloaded CSV remains on your computer until you delete it. It is a readable,
unencrypted file and may contain personal or sensitive information from your
conversations. A participant-ID filename does not anonymize the message contents.
The exporter does not add session authentication fields to the CSV, but it does
not redact personal information you have included in chat text.

Replika's own account information, storage and retention are controlled by
Replika, not this extension.

## Your Choices

You choose the date range and when to request an export. You can disable or
uninstall the extension to stop future extension activity. Existing downloaded
files are not removed when you uninstall; delete them separately when appropriate.
You choose whether and how to share a downloaded file.

## Changes And Contact

We will update this policy if the extension's data practices change and revise
the date above.

For questions about the extension or this policy, contact LinkLab at:
[sulinklab@gmail.com](mailto:sulinklab@gmail.com).
