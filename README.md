<h1 align="center">Hi, I'm Haekal 👋</h1>
<h3 align="center">Security Researcher • CS Student @ Universitas Cakrawala</h3>

<p align="center">
  🔐 Mobile (Android-focused) & Web Application Security &nbsp;|&nbsp; 🎓 Computer Science @ Universitas Cakrawala
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Breaking+Android+apps+responsibly+%F0%9F%93%B1;Deep+link+%26+WebView+exploitation;Bug+bounty+hunter+%40+Intigriti+%7C+Bugcrowd+%7C+HackerOne;CS+Student+%40+Universitas+Cakrawala" alt="Typing SVG" />
  </a>
</p>

---

### 🧠 About Me

- 🔭 I research and break mobile & web applications - Android, web, and occasionally iOS/Windows/Linux/macOS pentesting
- 🎯 Active on **Intigriti** (`daxxiee0_`), **Bugcrowd**
- 🛠️ Focus areas: deep link exploitation, WebView abuse, intent injection, exported component abuse, auth bypass, token leakage, taint-flow analysis, BOLA/BFLA
- 🧩 I also build offensive automation tooling (browser automation, fingerprint rotation, auth flow testing)
- 🌱 Student at **Universitas Cakrawala**, Computer Science program

---

### 🧪 Security Toolkit

<p align="left">
  <img src="https://img.shields.io/badge/Frida-black?style=for-the-badge&logo=frida&logoColor=white" />
  <img src="https://img.shields.io/badge/Objection-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JADX-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MobSF-darkred?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Ghidra-5A5A5A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/dnSpy-00599C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/radare2-grey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ADB-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
</p>

**Core skills:** Static analysis (JADX, APKTool, Smali) · Dynamic instrumentation (Frida/Objection hooking, overload resolution on obfuscated methods) · Deep link & intent exploitation · Exported activity/provider/receiver abuse · WebView `addJavascriptInterface` / `loadUrl` auditing · Parcelable/Serializable abuse · OAuth/PKCE flow analysis · Full taint-flow tracing (source → sink → trust boundary)

---

### 💻 Tech Stack

**Languages**
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
</p>

**Frontend**
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
</p>

**Database**
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Hosting / Infra**
<p align="left">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

**Automation / Research Tooling**
<p align="left">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Camoufox-444?style=for-the-badge" />
</p>

---

### 🏆 Bug Bounty Highlights

- **Okta Verify (Android)** — Bugcrowd — confirmed `UriEnrollmentActivity` deep link (`oktaverify://`) registered `BROWSABLE` without `autoVerify`, allowing any web page to trigger enrollment
- **Capital.com (Android)** — Intigriti — hardcoded UAEPass OAuth client secret in production APK, confirmed via live token retrieval; identified a secondary PKCE-absent authorization code interception chain with a full Kotlin PoC
- **Dropbox (Android)** — Intigriti — exported `FileCacheProvider` vulnerability (CWE-284, CVSS 6.8 High), validated with a full Kotlin PoC
- **Canva (Android)** — Bugcrowd — Frida instrumentation research, including dynamic overload resolution for obfuscated methods

---

### 🚧 Current Project

**SpeakUp** (formerly VoxCoach) — AI-driven public speaking coaching platform combining speech analysis (Whisper ASR, librosa, MediaPipe FaceMesh, LLM-based scoring) with a human mentor marketplace. Targeting Android, Web, and Desktop.

---

<p align="center">
  <em>Breaking things responsibly, one CVE at a time.</em>
</p>
