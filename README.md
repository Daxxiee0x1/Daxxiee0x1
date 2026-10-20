<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=1200&color=C9D1D9&background=00000000&center=true&vCenter=true&width=600&height=50&lines=Hi%2C+I'm+Daxxiee;Security+Researcher;Android+%2B+Web+Pentester" alt="Typing SVG" />

<sub>Bug bounty hunter · Reverse engineering · Mobile application security</sub>

</div>

<div align="center">

<img src="./assets/banner.gif" alt="Banner" width="100%" />

</div>

<br>

## About Me

- 🔭 **Currently working on:** Local Code Workspace
- 🌱 **Currently learning:** Cyber Security
- 🎯 **Focus:** Android app security, web security, penetration testing
- 💬 **Ask me about:** Deep links, intent/WebView exploitation, OAuth/PKCE flows
- 🏴 **Platforms:** Intigriti (`daxxiee0_`) · Bugcrowd

<br>

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Daxxiee0x1&show_icons=true&hide_border=true&bg_color=0d1117&title_color=c9d1d9&icon_color=8b949e&text_color=8b949e&ring_color=c9d1d9&cache_seconds=86400" width="49%" />
<img src="https://streak-stats.demolab.com/?user=Daxxiee0x1&hide_border=true&background=0d1117&ring=c9d1d9&fire=c9d1d9&currStreakLabel=c9d1d9&sideLabels=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" width="49%" />

</div>

<br>

## Tech Stack

<div align="center">

<img src="./assets/tech-stack.svg" alt="Tech stack" width="100%" />

</div>

<br>

## Research Highlights

| Target | Platform | Finding |
|:--|:--|:--|
| Okta Verify (Android) | Bugcrowd | `UriEnrollmentActivity` deep link (`oktaverify://`) registered BROWSABLE without `autoVerify`, so any web page can trigger enrollment · **P3** |
| Capital.com (Android) | Intigriti | Hardcoded OAuth client secret in production APK, confirmed via live token retrieval · PKCE-absent auth code interception chain, validated with a Kotlin PoC |
| Dropbox (Android) | Intigriti | Exported `FileCacheProvider` (CWE-284, CVSS 6.8 High), validated with a Kotlin PoC |
| Canva (Android) | Bugcrowd | Frida instrumentation research, including dynamic overload resolution for obfuscated methods |

<br>

## Approach

Static analysis (JADX, APKTool, Smali) → dynamic instrumentation (Frida, Objection) → full taint flow tracing from source to sink across every trust boundary. A finding is only a finding once it is reachable and demonstrated.

<br>

<div align="center">

<sub>Stay curious. Verify everything.</sub>

</div>
