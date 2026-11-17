# Third-party redistribution information

DonkeySHAT's proprietary freeware notice applies to first-party material.
It does not restrict independent third-party rights. All seven original artwork
assets are approved by the owner for distribution with DonkeySHAT.

| Included component | Required notice handling |
| --- | --- |
| WebView2 SDK 1.0.3537.50 Core/WinForms/Wpf assemblies and x64 WebView2Loader.dll (two locations) | Retain licenses/WebView2/LICENSE.txt and NOTICE.txt. Binary redistribution must reproduce the copyright, conditions and disclaimer. Do not imply Microsoft/contributor endorsement. |
| Application-specific .NET 10.0.12 win-x64 apphost | Retain the .NET Foundation MIT copyright and permission notice supplied in licenses/DOTNET-RUNTIME-MIT.txt and the companion release notice. |

Existing licenses/LICENSE.txt (Microsoft .NET Library terms) and collective
ThirdPartyNotices.txt are also preserved unchanged. They originated with the
earlier runtime-inclusive package; their presence does not establish that all
components they mention remain bundled. In particular, do not infer that the
Microsoft .NET Library downstream-agreement/indemnity requirements apply to the
MIT apphost merely from that legacy file. If another component is later added
under those terms, assess those requirements before distributing it.

Not bundled: .NET Core/Desktop runtime, hostfxr, hostpolicy, coreclr, D3DCompiler,
WebView2 browser Runtime, Codex CLI, Node or credentials. Those external products
and services retain their own terms. No previous runtime-removal investigation
is reopened here.

Primary references checked for the remaining components:

- [Exact WebView2 package license](https://www.nuget.org/packages/Microsoft.Web.WebView2/1.0.3537.50/License)
- [.NET runtime v10.0.12 MIT license](https://github.com/dotnet/runtime/blob/v10.0.12/LICENSE.TXT)

Download and preserve THIRD-PARTY-NOTICES-v0.2.3.txt alongside the unchanged ZIP.
It supplies the apphost MIT notice missing from the archive's legacy notice set.
No application-source disclosure requirement was identified in these component
licenses. This inventory is a distribution review, not a legal opinion.
