# Crisper — releases

Downloads and the update feed for [Crisper](https://crisperflow.com), an ambient
contextual memory app for macOS.

- **Download the latest build:** [Releases](https://github.com/jithinio/crisperflow-releases/releases/latest)
- **Update feed:** <https://updates.crisperflow.com/appcast.xml>

Crisper updates itself through [Sparkle](https://sparkle-project.org). Every
build is signed with a Developer ID certificate, notarized by Apple, and the
feed is signed with an EdDSA key the app verifies before it will install
anything.

This repository holds published artefacts only — the source lives elsewhere.
Everything here is written by `Scripts/release.sh`; nothing is edited by hand.

## Requirements

macOS 26.0 or later. Apple silicon with Apple Intelligence enabled unlocks
on-device classification; without it the app falls back to a heuristic
classifier and everything else works unchanged.
