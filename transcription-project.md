---
layout: page
title: The Transcription Project
permalink: /transcription-project.html
---

Node 588416 hosts an experimental AI-assisted net-transcription and
summary pipeline: per-transmission audio is captured, transcribed locally
with Whisper, and made available for review. No cloud AI service sees raw
audio as part of this pipeline.

**Write-up:** the full series is published on
[EtherHam](https://etherham.com/tag/net-logging/) —
[Part 1](https://etherham.com/automatic-net-logging-part-1-who-its-for-and-getting-audio-out-of-a-hub-node/)
covers what it's for and how audio is captured off the hub node, with
later parts covering transcription, callsign resolution, and lessons
learned. 

**Code:** the pipeline is a fork of Hunter Inman's (KK7NQN) original
project, extended and fixed for this node's setup, published at
[EtherHamRadio/KK7NQN-TranscriptionLogger](https://github.com/EtherHamRadio/KK7NQN-TranscriptionLogger).

See [Disclaimers](disclaimers.html) for what this service is not intended
to be used for.
