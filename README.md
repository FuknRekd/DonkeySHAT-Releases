# DonkeySHAT v0.2.3

DonkeySHAT is a Windows desktop workspace for manually coordinating AI planning
and Codex execution. This first public release supports **Manual Mode only**. You plan in SHAT,
transfer a bounded task to Donkey, monitor execution and review the result yourself.
Full automation is disabled.

## Download and install

Open this repository's **Releases** page and select **DonkeySHAT v0.2.3**.
Download DonkeySHAT-v0.2.3-win-x64.zip, SHA256SUMS.txt and THIRD-PARTY-NOTICES-v0.2.3.txt.
GitHub's automatically generated source archives contain distribution documents,
not the application or its source code.

Requires Windows x64, **.NET 10 Windows Desktop Runtime x64**, Microsoft WebView2
Runtime, configured Codex CLI and your own authentication. No credentials,
provider subscription or runtime installation is supplied.
See [installation](docs/INSTALLATION.md), [release notes](docs/RELEASE-NOTES-v0.2.3.md),
[limitations](docs/KNOWN-LIMITATIONS.md) and [third-party notices](docs/THIRD-PARTY.md).

The public download is named DonkeySHAT-v0.2.3-win-x64.zip. This documentation-only repack removes obsolete private-review holds while preserving application binaries, artwork and required third-party notices. No additional functional test pass is claimed.

Tasks can change files with your user permissions. Use backups and review results.
Never post credentials, browser profiles, private task history or proprietary files
in public issues. Sanitize any diagnostic excerpt before sharing it.

## How DonkeySHAT Works

### 1. Choose a Folder
![Choose a Folder](images/Choose%20a%20Folder.jpg)

### 2. Give SHAT an Idea
Tell it to give you a prompt to do what you want to do (i.e. Make the game Tetris in a stand alone, offline web page)
![Give SHAT an Idea](images/Give%20SHAT%20an%20idea.jpg)

### 3. Give the Prompt to Donkey
Copy the prompt from SHAT and paste it into Donkey.
![Give Prompt to Donkey](images/Give%20promtp%20to%20Donkey.jpg)

When Donkey finishes, you can review the output, copy the run to your clipboard then paste it back into SHAT 

There's a LOT more planned for DonkeySHAT, please Star and Watch.

Copyright © 2026 Matt Finley. All rights reserved.
**Proprietary freeware:** free to download and use. Application source remains private.
This repository contains distribution materials only, with no development history.
Third-party components retain their independent license rights.
for more work, then paste that prompt back to Donkey, and so on. 
