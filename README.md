# Z1 Reignited assets

Public, hash-addressed project update files for [Z1 Reignited](https://z1reignited.win/).
The launcher obtains its manifest and download routing from the trusted game API,
then verifies every file's size and SHA-256 before installing it. No GitHub login
or publisher credential is required by players.

Large files are Release assets; they are never committed to Git. The source and
player release repositories remain private. This repository contains no accounts,
saved logins, game settings, server configuration, VM access, or publisher keys.

Stock August 2017 files continue to come from Steam using each player's own Steam
account. Updates include complete modified game containers to preserve compatibility;
the projectPatch marker describes delivery provenance. It is not a statement that
every byte in a modified container was authored by this project. Existing game and
third-party rights/notices remain applicable; these files are not relicensed.

Release object names are uppercase SHA-256 values. Release tags identify the
trusted manifest build. Existing object identities must never be overwritten.
