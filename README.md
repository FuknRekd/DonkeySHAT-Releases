# DonkeySHAT v0.2.3

**Two AIs. One window. Zero tolerance for bullshit.**

DonkeySHAT brings ChatGPT and Codex CLI together in one Windows desktop application.

**SHAT** (Strategic Human-AI Taskmaster) handles planning, strategy, and reviewing results using regular ChatGPT Chat Mode.

**Donkey** handles the dirty work. It executes tasks through Codex CLI, works with files, runs commands, and reports what happened.

You keep both jackasses honest.

**Plan it. Run it. Verify it.**

## Download and Install

Download the latest version from the [DonkeySHAT Releases page](https://github.com/FuknRekd/DonkeySHAT-Releases/releases).

**Requirements:**

- Windows 64-bit
- [.NET 10 Desktop Runtime (x64)](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
- [OpenAI Codex CLI](https://github.com/openai/codex)
- Your own ChatGPT and Codex authentication

Download `DonkeySHAT-v0.2.3-win-x64.zip`, extract it into a folder, and run `App/Launch-Manual.cmd`.

See the [detailed installation guide](docs/INSTALLATION.md) if you need help configuring the prerequisites.

## How DonkeySHAT Works

### 1. Choose a Folder

Select the folder where Donkey will work. This can be an existing project or a new project you're starting from scratch.

![Choose a Folder](images/Choose%20a%20Folder.jpg)

### 2. Give SHAT an Idea

Tell SHAT what you want to accomplish.

For example:

*"Give me a Donkey prompt to create a standalone, offline web-based Tetris game."*

SHAT develops the instructions for Donkey. You can discuss the approach, refine requirements, and decide what Donkey should do.

![Give SHAT an Idea](images/Give%20SHAT%20an%20idea.jpg)

### 3. Give the Prompt to Donkey

Copy SHAT's instructions into Donkey and submit the task.

Donkey executes the work while DonkeySHAT displays its activity, progress, and results.

![Give Prompt to Donkey](images/Give%20promtp%20to%20Donkey.jpg)

### 4. Review and Repeat

When Donkey finishes, review its results.

Use **Copy This Run** to copy the execution report and paste it into SHAT.

SHAT reviews what actually happened, identifies problems, and prepares the next task if needed.

Repeat until the job is finished and verified.

That's the idea: **SHAT is strategic. Donkey is tactical. You're in charge.**

## Current Version: v0.2.3

This release supports **Manual Mode**, where you transfer instructions and results between SHAT and Donkey.

Full automation is still under development.

Known limitations include some reporting display issues, limited text selection in completion notifications, and no embedded interactive CLI terminal yet.

See the [known limitations](docs/KNOWN-LIMITATIONS.md) and [release notes](docs/RELEASE-NOTES-v0.2.3.md).

## What's Next?

There's a LOT more planned for DonkeySHAT, including interactive terminals, improved reporting, and automated SHAT/Donkey collaboration.

**Star this repository** if you like the project. **Watch** it for future releases.

## License

Copyright © 2026 Matt Finley. All rights reserved.

DonkeySHAT is **proprietary freeware**, free to download and use. Its application source code remains private.

Third-party software retains its independent license rights. See the [third-party notices](docs/THIRD-PARTY.md).
