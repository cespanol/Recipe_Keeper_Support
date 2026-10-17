---
layout: default
title: Recipe Keeper Simplified Privacy Policy
---

# Recipe Keeper Simplified Privacy Policy

Effective: October 16, 2026

Recipe Keeper Simplified is a private, personal recipe notebook. It does not contain ads, track you across apps or websites, or use a third-party analytics SDK.

## Recipe data

Recipes and app preferences are stored on your device. When iCloud is available, Recipe Keeper uses Apple's private CloudKit storage so the same library can be available on your devices signed in to the same iCloud account. The developer does not operate a separate recipe-content server and does not use your recipes for advertising, analytics, or model training.

## Imports

- Photos and camera scans are processed on-device for text recognition. Images selected for import are not retained as recipe attachments by default.
- Supported Apple Foundation Models processing, when available, runs on-device and is requested separately from initial text recognition. Proposed changes require your approval.
- Pasted text is used to create the draft you review. Keeping original text with a saved recipe is optional and off by default; ordinary recipe sharing and library backups exclude that original text.
- While you review an import, current recipe fields are saved locally for interrupted-import recovery. This keeps at most one pending draft and excludes original text/images, unassigned source text, previews, and Undo history by default. Pending fields expire seven days after the last edit or resume.
- Choosing Save for Later with “Keep original source with this draft for 7 days” enabled separately retains the original import text and available source images locally for seven days from that choice. Ordinary edits do not extend source retention. Pending drafts and retained source are excluded from device backup and iCloud synchronization. Successful save or explicit discard triggers cleanup; expiry cleanup runs when the app is used. Temporary working sources created by correction or reacquisition are not retained with the draft.
- When you ask Recipe Keeper to import a link, the app contacts that website to retrieve the page. The website may receive ordinary request information such as your IP address and user agent under its own privacy policy. Recipe Keeper does not send the page or recipe to a developer-operated service.
- Temporary import and sharing files are removed when they are no longer needed. Saved recipe fields remain until you edit or delete them.

## Manual recipe drafts

The manual editor saves unfinished recipe fields and row structure locally for recovery. New recipes and edits use separate draft identities. A draft remains until Save, Discard, or Delete All Data. It has no age-based expiry.

Manual drafts are excluded from iCloud sync and device backup. They do not contain source images, private Original Text, model proposals, or Undo history. An explicit request to clear saved Original Text is stored as a choice only. The app keeps the saved recipe unchanged until Save.

An older edit draft must not overwrite a recipe that changed elsewhere. The app checks the saved recipe before recovery and saving.

## Diagnostics

Recipe Keeper records content-free event codes and coarse timing information in Apple's unified logging system to help diagnose failures. It does not intentionally log recipe titles or content, import text, source links, profile information, clipboard contents, filenames or paths, images, or CloudKit identifiers. Apple may make crash and TestFlight diagnostics available when a tester or device owner chooses to share them.

## Permissions

Photo-library access is used only for recipe images you choose. Camera access is used only when you start a scan. You can change permission access in system Settings.

## Deletion and recovery

Delete All Data clears local manual drafts, pending import fields, and explicitly retained import source before removing library records. The app reports cleanup or save failures. A failure can leave some data in place. External backup files remain under your control.

Deleted recipes move to Recently Deleted for 30 calendar days. You can restore them during that period. After the deadline, the app removes them when it opens or returns to the foreground. A delayed or failed cleanup can leave a recipe recoverable until removal succeeds. Delete Now removes a recipe permanently. Deletion may sync through iCloud to your other devices.

Library backup files are controlled by you and the destination you select. Ordinary sharing and library backups exclude private Original Text. Before reinstalling during a storage problem, contact support so recovery options can be checked first.

## Support

For private help, email [info@cespanol.com](mailto:info@cespanol.com?subject=Recipe%20Keeper%20Simplified%20Support). Contact Support opens your email app with a product-name subject. It does not attach recipes, images, links, or diagnostics. You choose what to send. Your email provider and the support mailbox handle the message. The developer uses the information you send to answer your request. Contact the same address for questions about support-message deletion.

The public [help website](https://cespanol.github.io/Recipe_Keeper_Support/support/) remains available. GitHub issues are optional and public. Keep private recipes, photos, source links, iCloud identifiers, and account details out of public issues.

This policy will be updated before release if the app's data handling changes.
