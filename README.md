# Sprint Drift

**Keep the reason you started in view—even when the work changes shape.**

You begin with one intention. Then a question, interruption, or useful side
task pulls the work somewhere else. Sprint Drift helps you keep the original
thread, capture what happened, and return without reconstructing everything
from memory.

## Download

[Download the latest signed and notarized release](https://github.com/jerrytmcl/Sprint-Drift-Downloads/releases/latest).

The current release is **Sprint Drift 0.1.1**. It requires macOS 15 or later
on Apple silicon.

## Why use it?

- Keep your intention visible in a small floating timer.
- Add a quick note when a decision, detour, or discovery matters.
- Park a side idea without abandoning the work in front of you.
- Pause with enough context to remember what was happening when you return.
- End with a chronological trail instead of only a stopped timer.
- Keep the record locally accessible and under your control.

Sprint Drift does not block apps, watch your screen, or score your focus. It
does not decide whether a detour was useful. It gives you enough context to make
that judgment yourself and choose a sensible next step.

## How it works

1. Set an intention and choose a duration.
2. Work with the compact timer nearby.
3. Add typed notes, optional local voice notes, or parked Sparks as needed.
4. Review what happened and add a reflection only if it helps.
5. Continue the intention, start something new, or stop for now.

Nothing starts automatically.

## Private by default

Sprint Drift has no account, built-in sync, analytics, or cloud backup. Sprint
records stay locally accessible on your Mac. Optional voice capture uses a
separate 227.5 MB model that downloads only when you choose it; transcription
then runs on this Mac.

Read the plain-language [privacy and local-data notice](PRIVACY.md) for the
current storage, network, model, export, and deletion boundaries.

## Verify the download

Download both the DMG and its matching `.sha256` file, then run:

```sh
shasum -a 256 -c SprintDrift-<version>.dmg.sha256
```

## Support

For help, an idea, or a bug report, use the private
[feedback form](https://docs.google.com/forms/d/e/1FAIpQLSc6ykubkQNUf6M95oGK88mRHbiglO-qsZ9n4g0RY1G9Tlss3g/viewform).
The app menu can copy the non-sensitive version, build, macOS, and architecture
facts that are useful in a report. Read [Support](SUPPORT.md) before including
screenshots or logs.

## Uninstall

Quit Sprint Drift and move `SprintDrift.app` from Applications to the Trash.
Removing the app does not automatically remove your locally stored records,
downloaded voice model, exports, or chosen mirror folder. See
[Support](SUPPORT.md#uninstall-and-local-data) for the deliberate cleanup paths.

This repository contains downloads, signed update metadata, and release notes.
It intentionally contains no application source code. Sprint Drift is
proprietary software. All rights reserved.
