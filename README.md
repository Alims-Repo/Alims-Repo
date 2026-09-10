<div align="center">

# Abdul Alim

**Android & Kotlin Multiplatform Developer**

Building cross-platform mobile apps — and publishing the libraries I needed while building them.

[![Portfolio](https://img.shields.io/badge/Portfolio-alims--repo.github.io-7F52FF?style=flat-square&logo=github&logoColor=white)](https://alims-repo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdul_Alim-7F52FF?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-alim-monshi-5874511b2/)
[![Email](https://img.shields.io/badge/Email-sourav.0.alim-7F52FF?style=flat-square&logo=gmail&logoColor=white)](mailto:sourav.0.alim@gmail.com)
[![Maven Central](https://img.shields.io/badge/Maven_Central-io.github.alims--repo-7F52FF?style=flat-square&logo=apachemaven&logoColor=white)](https://central.sonatype.com/namespace/io.github.alims-repo)

`Dhaka, Bangladesh` · `BSc Computer Science, Green University` · `Available for freelance & full-time`

</div>

<br/>

---

## Featured Work

Four libraries for the Compose Multiplatform ecosystem — navigation, routing, and secure storage.

<br/>

### FlowTab-CMP · Animated bottom navigation for Compose Multiplatform

<div align="center">

| Light | Dark |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Alims-Repo/FlowTab-CMP/main/media/flowtab-demo-light.gif" width="230" alt="FlowTab light theme"/> | <img src="https://raw.githubusercontent.com/Alims-Repo/FlowTab-CMP/main/media/flowtab-demo.gif" width="230" alt="FlowTab dark theme"/> |

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/flowtab-cmp?style=flat-square&label=maven%20central&color=7F52FF)](https://central.sonatype.com/artifact/io.github.alims-repo/flowtab-cmp)
[![Stars](https://img.shields.io/github/stars/Alims-Repo/FlowTab-CMP?style=flat-square&color=7F52FF)](https://github.com/Alims-Repo/FlowTab-CMP/stargazers)
![Kotlin](https://img.shields.io/badge/Kotlin-2.3.21-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Compose Multiplatform](https://img.shields.io/badge/Compose_MP-1.11.0-7F52FF?style=flat-square)
![Platforms](https://img.shields.io/badge/Android_·_iOS-7F52FF?style=flat-square)

</div>

```kotlin
FlowTab(
    items = tabs,
    selected = current,
    onSelect = { current = it },
    indicator = Indicator.Ripple,
    style = FlowTabStyle.Glass   // Haze-backed blur, optional
)
```

Most navigation bars marry you to a navigation library. This one doesn't — it's pure state in, callbacks out, so it drops into Navigation3, Decompose, Voyager, PreCompose, Appyx, or plain Compose state without adapters.

- **Real glassmorphism** via [Haze](https://github.com/chrisbanes/haze), not a translucent overlay
- **Expandable search** that grows out of the bar, fully callback-driven
- **Three indicators** — ripple, dot, line — plus count and dot badges
- **One source set** for `iosArm64`, `iosX64`, `iosSimulatorArm64` and Android

[Documentation](https://alims-repo.github.io/FlowTab-CMP/) · [Source](https://github.com/Alims-Repo/FlowTab-CMP)

<br/>

---

<br/>

### NavEase · Annotation-driven navigation for Jetpack Compose

<div align="center">

[![Stars](https://img.shields.io/github/stars/Alims-Repo/NavEase?style=flat-square&color=7F52FF)](https://github.com/Alims-Repo/NavEase/stargazers)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Compose](https://img.shields.io/badge/Jetpack_Compose-7F52FF?style=flat-square&logo=jetpackcompose&logoColor=white)
![Status](https://img.shields.io/badge/status-in_development-orange?style=flat-square)

</div>

Compose navigation graphs are boilerplate: route constants, argument parsing, type-unsafe string keys, one giant `NavHost` that every screen has to be registered in by hand.

NavEase removes that layer. **Annotate your screens, and the routing is generated for you** — routes, arguments and the graph itself, checked at compile time instead of discovered at runtime.

Paired with FlowTab-CMP, it's the other half of the same problem: FlowTab handles what navigation *looks* like, NavEase handles how it's *wired*.

[Documentation](https://alims-repo.github.io/NavEase/) · [Source](https://github.com/Alims-Repo/NavEase)

<br/>

---

<br/>

### SecureVault-KMP · Secret storage with native backends

<div align="center">

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/secure-vault?style=flat-square&label=maven%20central&color=7F52FF)](https://central.sonatype.com/artifact/io.github.alims-repo/secure-vault)
![Kotlin](https://img.shields.io/badge/Kotlin-2.3-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Platforms](https://img.shields.io/badge/Android_·_iOS-7F52FF?style=flat-square)

</div>

```kotlin
val vault = SecureVault("com.acme.auth")

vault.put("session", token)
val session: String? = vault.get("session")
```

One coroutine-first API, two real platform backends: `EncryptedSharedPreferences` over the Android Keystore, and Keychain Services on iOS. **No hand-rolled cryptography** — the platform does the work it was designed to do. Ships an optional Compose Multiplatform integration as a separate artifact.

[Source](https://github.com/Alims-Repo/SecureVault-KMP)

<br/>

---

<br/>

### Prayer-Times-KMM · Islamic prayer time calculation

<div align="center">

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/prayer-times-kmm?style=flat-square&label=maven%20central&color=7F52FF)](https://central.sonatype.com/artifact/io.github.alims-repo/prayer-times-kmm)
[![Stars](https://img.shields.io/github/stars/Alims-Repo/Prayer-Times-KMM?style=flat-square&color=7F52FF)](https://github.com/Alims-Repo/Prayer-Times-KMM/stargazers)
![Platforms](https://img.shields.io/badge/Android_·_iOS_·_JVM-7F52FF?style=flat-square)

</div>

Adhan-inspired astronomical calculation, ported to common Kotlin. Solar-time math with **11+ calculation methods**, madhab selection for Asr, and proper high-latitude handling — the part most implementations get wrong. Zero platform dependencies, so the same result on every target.

[Documentation](https://alims-repo.github.io/Prayer-Times-KMM/) · [Source](https://github.com/Alims-Repo/Prayer-Times-KMM)

<br/>

---

## Also Built

| Project | What it is | |
|---|---|---|
| **[Smart Traffic Management System](https://github.com/Alims-Repo/Smart-Traffic-Management-System)** | Four-target KMP system — Android, iOS, Desktop and a Ktor server — for real-time monitoring, adaptive signal control and emergency vehicle priority | ![](https://img.shields.io/github/stars/Alims-Repo/Smart-Traffic-Management-System?style=flat-square&label=&color=7F52FF) |
| **[CallerID](https://github.com/Alims-Repo/CallerID)** | Caller identification and spam blocking for Android — real-time lookup, blocklists, contact management | ![](https://img.shields.io/github/stars/Alims-Repo/CallerID?style=flat-square&label=&color=7F52FF) |
| **[Bkash-Android-SDK](https://github.com/Alims-Repo/Bkash-Android-SDK)** | Drop-in Android SDK for bKash, Bangladesh's largest mobile payment gateway | ![](https://img.shields.io/github/stars/Alims-Repo/Bkash-Android-SDK?style=flat-square&label=&color=7F52FF) |
| **[Pdf-Generator](https://github.com/Alims-Repo/Pdf-Generator)** | Kotlin DSL for multi-page A4 PDFs on Android — tables, text, automatic pagination | ![](https://img.shields.io/github/stars/Alims-Repo/Pdf-Generator?style=flat-square&label=&color=7F52FF) |
| **[Crash-Guard](https://github.com/Alims-Repo/Crash-Guard)** | Android crash handling with customizable crash screens and persistent logging | ![](https://img.shields.io/github/stars/Alims-Repo/Crash-Guard?style=flat-square&label=&color=7F52FF) |
| **[TaskFlow](https://github.com/Alims-Repo/TaskFlow)** | Offline-first KMP task manager — shared domain, Compose on Android, SwiftUI on iOS, Room + Koin | ![](https://img.shields.io/github/stars/Alims-Repo/TaskFlow?style=flat-square&label=&color=7F52FF) |

<details>
<summary><b>Experiments & older work</b></summary>

<br/>

- **[RefactoringPlan](https://github.com/Alims-Repo/RefactoringPlan)** — a structured modernisation plan for a seven-year-old legacy Android codebase: architecture, dependency debt, performance
- **[Scrapper](https://github.com/Alims-Repo/Scrapper)** — video URL extraction from TikTok, Facebook, Instagram and X
- **[SmolChat-Android](https://github.com/Alims-Repo/SmolChat-Android)** *(fork)* — running GGUF-format SLMs/LLMs fully on-device; my sandbox for on-device AI

</details>

<br/>

---

## Toolbox

| | |
|---|---|
| **Languages** | Kotlin · Java · Swift · SQL |
| **UI** | Jetpack Compose · Compose Multiplatform · Material 3 · SwiftUI |
| **Cross-platform** | Kotlin Multiplatform · KMM · Ktor |
| **Architecture** | Clean Architecture · MVVM · MVI · Repository pattern |
| **Data & DI** | Room · SQLDelight · Koin · Firebase · DataStore |
| **Build & release** | Gradle (Kotlin DSL) · Maven Central publishing · GitHub Actions |

**Currently:** freelance Android development, maintaining the libraries above
**Learning:** Compose animation internals, deeper iOS interop, on-device AI

<br/>

---

## Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Alims-Repo&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=7F52FF&icon_color=7F52FF&text_color=8B949E&bg_color=00000000" alt="GitHub stats" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alims-Repo&layout=compact&hide_border=true&langs_count=6&title_color=7F52FF&text_color=8B949E&bg_color=00000000" alt="Top languages" height="160"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=Alims-Repo&hide_border=true&ring=7F52FF&fire=7F52FF&currStreakLabel=7F52FF&background=00000000&stroke=30363D&sideLabels=8B949E&dates=6E7681" alt="Contribution streak" height="160"/>

</div>

<br/>

---

<div align="center">

### Let's build something

Open to freelance work, full-time roles, and open-source collaboration.

[![Portfolio](https://img.shields.io/badge/Portfolio-7F52FF?style=for-the-badge&logo=github&logoColor=white)](https://alims-repo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7F52FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-alim-monshi-5874511b2/)
[![Email](https://img.shields.io/badge/Email-7F52FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sourav.0.alim@gmail.com)

<sub>A star on anything useful goes a long way.</sub>

</div>
