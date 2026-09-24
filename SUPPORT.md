# Sprint Drift support

Use the public [Sprint Drift issue
forms](https://github.com/jerrytmcl/Sprint-Drift-Downloads/issues/new/choose)
for installation problems, update problems, unclear behavior, and bugs.

Sprint Drift has no telemetry or automatic crash reporter. A useful report
includes:

- Sprint Drift version and build;
- macOS version and Mac architecture;
- the action you attempted;
- what you expected and what happened instead; and
- whether the problem repeats after quitting and reopening the app.

Use **Sprint Drift → Copy Support Information** to copy the first three system
facts without copying sprint content.

Do not include private intentions, notes, reflections, transcripts, recordings,
credentials, API keys, private repository names, personal file paths, or
unsanitized screenshots in a public issue.

## Current limits

- Public builds support Apple silicon and macOS 15 or later.
- There is no account, built-in sync, mobile app, analytics, or cloud backup.
- Voice capture is optional and needs a separate 227.5 MB model download.
- Sprint Drift checks a signed update feed and asks before installing an
  update.
- This is an early public preview; keep a separate backup of anything
  important.

## Uninstall and local data

To remove the app, quit Sprint Drift and move `SprintDrift.app` from
Applications to the Trash.

The app bundle and local data are separate. Removing the app does not delete
your records, exports, mirror folders, or downloaded model files.

Before removing local data, export anything you want to keep. Then quit Sprint
Drift. The canonical session archive is under:

```text
~/Library/Application Support/Sprint Drift
```

Optional model data is under:

```text
~/Library/Application Support/Sprint Drift/VoiceModels
```

Exports and chosen mirror folders must be removed separately from the
locations you selected. System backups or third-party sync services may retain
their own copies.
