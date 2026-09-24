# Sprint Drift privacy and local data

Sprint Drift is designed to work without an account, built-in sync, analytics,
cloud backup, or required cloud AI.

## What stays on this Mac

Your intentions, timing, typed notes, Sparks, pause context, voice transcripts,
reflections, and saved sprint trail are stored in Sprint Drift's local record.
Voice recordings are temporary transcription inputs and are not retained as
part of the sprint record.

The canonical record is stored separately from the app bundle in:

```text
~/Library/Application Support/Sprint Drift/sessions.json
```

Optional downloaded model files use Sprint Drift's Application Support data.

## Network use

The app checks a signed update feed hosted by GitHub. Normal network metadata,
such as an IP address and request headers, can therefore be visible to GitHub's
hosting infrastructure. Sprint Drift does not put intentions, notes, records,
recordings, or transcripts into the update request.

The optional voice model downloads only after you choose **Download voice
capture**. The download request contacts the model host, but it does not send
your intentions, notes, audio, or transcripts. Once installed, transcription
runs on this Mac.

## Exports and mirrors

Exports and a chosen-folder mirror create copies where you direct them. Those
locations may be synchronized by another service if you place them in a synced
folder. Sprint Drift does not control or automatically delete those copies.

## Access and deletion

You can inspect saved records, export them, reveal or copy the local archive
path, and delete individual records after confirmation. Removing the app does
not remove records or model files automatically. See [Support](SUPPORT.md) for
the complete manual cleanup paths.

## What Sprint Drift does not do

Sprint Drift does not watch your screen, inspect other applications, score your
focus, diagnose attention, create a manager dashboard, or silently send your
record to an AI provider.
