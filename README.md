# Switchboard

A meeting recorder for the Mac, iPhone and Apple Watch. Record from whichever device
is nearest and it is still one recording, one transcript, one summary.

Transcription runs on your own machine and the audio never leaves it. Summaries are the
one exception, and they go to the model provider *you* configure with *your* key.

This repository hosts the macOS download and the website. The source lives elsewhere.

Website: https://cultivarium.github.io/switchboard-app/

## Download

**[Switchboard 0.1 (build 99) for macOS](../../releases/latest)** — open the `.dmg`
and drag Switchboard to Applications.

Requires macOS 15 or later. Apple Silicon recommended, since transcription runs locally.

The app is signed and notarized by Apple, so it opens on first launch with no
right-click-to-open dance.

## iPhone and Apple Watch

Those ship through TestFlight: https://testflight.apple.com/join/Hjx8BgBE

## What it does

- records your microphone and system audio as separate tracks, so remote and in-room
  voices stay distinguishable
- transcribes on device
- writes the meeting summary with your own API key
- posts that summary to a Slack channel you choose, per meeting series
- sends transcripts to agentdoc, and answers questions across all of them
