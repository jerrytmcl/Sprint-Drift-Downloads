# Sprint Drift

Official downloads and the signed update feed for the closed-source Sprint
Drift Mac app.

## Download

Download the latest signed and notarized DMG from
[Releases](https://github.com/jerrytmcl/Sprint-Drift-Downloads/releases/latest).

Sprint Drift currently requires macOS 15 or later on Apple silicon.

The matching `.sha256` file can be checked after downloading both files:

```sh
shasum -a 256 -c SprintDrift-<version>.dmg.sha256
```

## Privacy and support

Sprint records stay locally accessible on your Mac. Sprint Drift has no
account, built-in sync, analytics, or cloud backup. Optional voice capture uses
a separately downloaded model and transcribes on this Mac.

For help or a bug report, use
[Issues](https://github.com/jerrytmcl/Sprint-Drift-Downloads/issues). Do not
include private intentions, notes, transcripts, recordings, credentials, or
unsanitized screenshots in a public issue.

This repository intentionally contains no application source code. Its small
set of checked-in files exists only to serve Sprint Drift's signed update feed
and release notes. Sprint Drift is proprietary software. All rights reserved.
