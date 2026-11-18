# Versify Offline AI for Windows

Installable Windows x64 software with the presentation studio, five Bible translations, Gemma 3 4B, and the local AI/document runtime.

## Install

Open [the latest release](https://github.com/kelvinmacwan007/versify-releases/releases/latest). Download the `Offline-AI-Setup` EXE and **every matching BIN part** into the same folder. Keep the filenames unchanged, then run the EXE. The full package installs without an AI model download or separate Python/Ollama setup. We recommend 16 GB RAM.

## Update

In Versify, choose **Help > Check for Updates**. Confirm **Download and install**. The smaller update preserves your local library and existing offline model. The `App-Update` EXE requires an existing full installation. New builds are published by the private source repository after successful main-branch builds.

## Publish songs to the live library

Choose **File > AI Song Administrator (Live)**. Sign in with your live website administrator account, prepare a song using the local AI, review it, then choose **Publish to live library**. Published songs are available on [the live Songs page](https://versify.knorvix.com/songs). Live sign-in, publishing and URL imports need internet.

**Offline AI (Local Library)** saves only to this PC. Neither mode publishes an unconfirmed draft. The first AI response can take a few minutes on a CPU.

Source code is maintained separately in a private repository. This repository contains installers, checksums and update information. See the bundled model/runtime terms and Bible copyright metadata.
