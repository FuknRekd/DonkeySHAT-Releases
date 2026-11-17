# Installation

1. Use a Windows x64 desktop with the prerequisites below installed through your
   normal authorized installation process.
2. Download DonkeySHAT-v0.2.3-win-x64.zip, SHA256SUMS.txt and THIRD-PARTY-NOTICES-v0.2.3.txt. Keep the companion third-party notice
   with the application when retaining or redistributing the download.
3. In PowerShell, run `Get-FileHash -Algorithm SHA256 -LiteralPath '<downloaded ZIP path>'`.
   Compare the complete hash with SHA256SUMS.txt and the release description.
4. Extract the entire ZIP into a new writable folder. Do not run from the ZIP or
   overwrite an existing/running deployment. Keep the App and licenses folders intact.
5. Run `App/Launch-Manual.cmd`. The launcher uses normal installed .NET discovery.
6. Configure/authenticate your own Codex CLI and sign in to embedded ChatGPT with
   your own account as needed. These are separate sign-ins; no shared account is provided.
7. Select a working folder, transfer a bounded task manually, start Donkey, monitor
   activity, inspect Results & Reports and manually return evidence to SHAT.

## Prerequisites

- Windows x64; no ARM64, x86 or broad Windows-version certification is claimed.
- [.NET 10 Windows Desktop Runtime x64](https://dotnet.microsoft.com/en-us/download/dotnet/10.0).
  Select **Desktop Runtime**, not only the base or ASP.NET Runtime. An SDK is not required.
- [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).
- [Codex CLI](https://developers.openai.com/codex/cli), installed and configured
  for the installed execution profile. Node is needed if required by your Codex installation method.
- Your own authentication, required service access/entitlements and network access.

This framework-dependent ZIP bundles neither the .NET runtime nor the WebView2
browser runtime, Codex CLI, Node or authentication. Installed mode uses normal
Codex configuration/authentication and application-owned local settings/browser
storage. It is not a no-trace or isolated execution environment.

If startup fails, check prerequisites first. The executable is unsigned and may
trigger Windows reputation warnings; no SmartScreen reputation is claimed.
Use your normal security policy when deciding whether to run it.
