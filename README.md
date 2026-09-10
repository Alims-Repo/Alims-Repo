<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,50:5B2AB8,100:7F52FF&text=Abdul%20Alim&fontSize=58&fontColor=FFFFFF&fontAlignY=34&desc=Android%20%C2%B7%20Kotlin%20Multiplatform%20%C2%B7%20Compose&descAlignY=54&descSize=18&animation=fadeIn" width="100%" alt="Abdul Alim"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=7F52FF&center=true&vCenter=true&width=620&lines=Building+cross-platform+mobile+apps;Publishing+KMP+libraries+to+Maven+Central;Compose+Multiplatform+%E2%80%94+Android+%2B+iOS" alt="Typing SVG"/>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-7F52FF?style=for-the-badge&logo=github&logoColor=white)](https://alims-repo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7F52FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-alim-monshi-5874511b2/)
[![Email](https://img.shields.io/badge/Email-7F52FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sourav.0.alim@gmail.com)
[![Maven Central](https://img.shields.io/badge/Maven_Central-7F52FF?style=for-the-badge&logo=apachemaven&logoColor=white)](https://central.sonatype.com/namespace/io.github.alims-repo)

<img src="https://img.shields.io/badge/Dhaka,_Bangladesh-1a1b27?style=flat-square&logo=googlemaps&logoColor=7F52FF" />
<img src="https://img.shields.io/badge/BSc_CS_—_Green_University-1a1b27?style=flat-square&logo=graduationcap&logoColor=7F52FF" />
<img src="https://img.shields.io/badge/Open_to_work-1a1b27?style=flat-square&logo=statuspage&logoColor=7F52FF" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

# 🚀 Featured Projects

<br/>

## 🎨 FlowTab-CMP

<div align="center">

### *Animated bottom navigation for Compose Multiplatform*

<table width="100%">
<tr>
<td align="center" width="50%">
<img src="https://raw.githubusercontent.com/Alims-Repo/FlowTab-CMP/main/media/flowtab-demo-light.gif" width="240" alt="FlowTab light theme"/>
<br/><sub><b>Light</b></sub>
</td>
<td align="center" width="50%">
<img src="https://raw.githubusercontent.com/Alims-Repo/FlowTab-CMP/main/media/flowtab-demo.gif" width="240" alt="FlowTab dark theme"/>
<br/><sub><b>Dark</b></sub>
</td>
</tr>
</table>

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/flowtab-cmp?style=for-the-badge&label=MAVEN%20CENTRAL&color=7F52FF&labelColor=1a1b27)](https://central.sonatype.com/artifact/io.github.alims-repo/flowtab-cmp)
[![Stars](https://img.shields.io/github/stars/Alims-Repo/FlowTab-CMP?style=for-the-badge&color=7F52FF&labelColor=1a1b27)](https://github.com/Alims-Repo/FlowTab-CMP/stargazers)
![Platforms](https://img.shields.io/badge/ANDROID_·_iOS-7F52FF?style=for-the-badge&labelColor=1a1b27)

</div>

```kotlin
FlowTab(
    items     = tabs,
    selected  = current,
    onSelect  = { current = it },
    indicator = Indicator.Ripple,
    style     = FlowTabStyle.Glass   // Haze-backed blur, optional
)
```

> Most navigation bars marry you to a navigation library. This one doesn't — pure state in, callbacks out.
> It drops into **Navigation3, Decompose, Voyager, PreCompose, Appyx** or plain Compose state with no adapters.

<table width="100%">
<tr>
<td width="25%" align="center">🎭<br/><b>Glassmorphism</b><br/><sub>Real blur via Haze,<br/>not a fake overlay</sub></td>
<td width="25%" align="center">🔍<br/><b>Expandable search</b><br/><sub>Grows out of the bar,<br/>callback-driven</sub></td>
<td width="25%" align="center">✨<br/><b>3 indicators</b><br/><sub>Ripple · Dot · Line<br/>+ count & dot badges</sub></td>
<td width="25%" align="center">📱<br/><b>One source set</b><br/><sub>Android + all three<br/>iOS targets</sub></td>
</tr>
</table>

<div align="center">

[**📖 Docs**](https://alims-repo.github.io/FlowTab-CMP/) &nbsp;·&nbsp; [**💻 Source**](https://github.com/Alims-Repo/FlowTab-CMP)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

## 🧭 NavEase

<div align="center">

### *Annotation-driven navigation for Jetpack Compose*

![Status](https://img.shields.io/badge/STATUS-IN_DEVELOPMENT-FFA657?style=for-the-badge&labelColor=1a1b27)
![Compose](https://img.shields.io/badge/JETPACK_COMPOSE-7F52FF?style=for-the-badge&labelColor=1a1b27)
![KSP](https://img.shields.io/badge/CODEGEN-7F52FF?style=for-the-badge&labelColor=1a1b27)

</div>

> **Annotate your screens. NavEase generates the rest.**

Compose navigation is boilerplate: route constants, manual argument parsing, type-unsafe string keys, and one giant `NavHost` every screen has to be registered in by hand. NavEase deletes that layer — routes, arguments and the graph itself are **generated at compile time**, so a broken route is a build error instead of a crash in production.

<table width="100%">
<tr>
<th width="20%" align="left">&nbsp;</th>
<th width="40%" align="left">❌ &nbsp;Plain Compose Navigation</th>
<th width="40%" align="left">✅ &nbsp;With NavEase</th>
</tr>
<tr>
<td align="left"><b>Routes</b></td>
<td align="left"><sub>Hand-written string constants, duplicated across the codebase</sub></td>
<td align="left"><sub>Generated from the annotation on the screen itself</sub></td>
</tr>
<tr>
<td align="left"><b>Arguments</b></td>
<td align="left"><sub>Manual parsing and unchecked casts out of the bundle</sub></td>
<td align="left"><sub>Typed accessors, generated alongside the route</sub></td>
</tr>
<tr>
<td align="left"><b>Graph</b></td>
<td align="left"><sub>One giant <code>NavHost</code>, every screen registered by hand</sub></td>
<td align="left"><sub>Assembled at compile time — nothing to register</sub></td>
</tr>
<tr>
<td align="left"><b>A typo costs</b></td>
<td align="left"><sub>A crash, in production, on a screen you didn't test</sub></td>
<td align="left"><sub>A build error, on your machine, in seconds</sub></td>
</tr>
</table>

Paired with FlowTab-CMP it's the other half of one problem — **FlowTab handles what navigation looks like, NavEase handles how it's wired.**

<div align="center">

[**📖 Docs**](https://alims-repo.github.io/NavEase/) &nbsp;·&nbsp; [**💻 Source**](https://github.com/Alims-Repo/NavEase)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

<div align="center">

## 🔐 SecureVault-KMP &nbsp;·&nbsp; 📿 Prayer-Times-KMM

</div>

<table width="100%">
<tr>
<td width="50%" valign="top">

**🔐 SecureVault-KMP**

```kotlin
val vault = SecureVault("com.acme.auth")
vault.put("session", token)
val s: String? = vault.get("session")
```

One coroutine-first API, two **real** platform backends — `EncryptedSharedPreferences` over the Android Keystore, Keychain Services on iOS. No hand-rolled cryptography. Optional Compose Multiplatform integration ships separately.

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/secure-vault?style=flat-square&label=maven&color=7F52FF&labelColor=1a1b27)](https://central.sonatype.com/artifact/io.github.alims-repo/secure-vault)

</td>
<td width="50%" valign="top">

**📿 Prayer-Times-KMM**

```kotlin
val times = PrayerTimes(
    coordinates = Coordinates(23.81, 90.41),
    method = CalculationMethod.KARACHI
)
```

Adhan-inspired astronomical math ported to common Kotlin — **11+ calculation methods**, madhab selection for Asr, and correct high-latitude handling, the part most implementations get wrong.

[![Maven Central](https://img.shields.io/maven-central/v/io.github.alims-repo/prayer-times-kmm?style=flat-square&label=maven&color=7F52FF&labelColor=1a1b27)](https://central.sonatype.com/artifact/io.github.alims-repo/prayer-times-kmm)

</td>
</tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

# 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,java,swift,androidstudio,gradle,firebase&theme=dark" alt="Languages and tools"/>
<br/>
<img src="https://skillicons.dev/icons?i=idea,xcode,git,github,figma,postman&theme=dark" alt="Tooling"/>

</div>

<table width="100%">
<tr><td width="22%"><b>UI</b></td><td>Jetpack Compose · Compose Multiplatform · Material 3 · SwiftUI</td></tr>
<tr><td><b>Cross-platform</b></td><td>Kotlin Multiplatform · KMM · Ktor</td></tr>
<tr><td><b>Architecture</b></td><td>Clean Architecture · MVVM · MVI · Repository pattern</td></tr>
<tr><td><b>Data & DI</b></td><td>Room · SQLDelight · Koin · DataStore · Firebase</td></tr>
<tr><td><b>Release</b></td><td>Gradle Kotlin DSL · Maven Central publishing · GitHub Actions</td></tr>
</table>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

# 📦 Also Built

<table width="100%">
<tr>
<td width="33%" valign="top" align="center">

**🚦 [Smart Traffic System](https://github.com/Alims-Repo/Smart-Traffic-Management-System)**

<sub>Four-target KMP — Android, iOS, Desktop, Ktor server. Real-time monitoring, adaptive signals, emergency priority.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/Smart-Traffic-Management-System?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
<td width="33%" valign="top" align="center">

**📞 [CallerID](https://github.com/Alims-Repo/CallerID)**

<sub>Caller identification and spam blocking for Android — real-time lookup, blocklists, contact management.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/CallerID?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
<td width="33%" valign="top" align="center">

**💳 [Bkash SDK](https://github.com/Alims-Repo/Bkash-Android-SDK)**

<sub>Drop-in Android SDK for bKash, Bangladesh's largest mobile payment gateway.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/Bkash-Android-SDK?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
</tr>
<tr>
<td valign="top" align="center">

**📄 [Pdf-Generator](https://github.com/Alims-Repo/Pdf-Generator)**

<sub>Kotlin DSL for multi-page A4 PDFs on Android — tables, text, auto-pagination.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/Pdf-Generator?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
<td valign="top" align="center">

**🛡️ [Crash-Guard](https://github.com/Alims-Repo/Crash-Guard)**

<sub>Android crash handling with customizable crash screens and persistent logging.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/Crash-Guard?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
<td valign="top" align="center">

**✅ [TaskFlow](https://github.com/Alims-Repo/TaskFlow)**

<sub>Offline-first KMP task manager — Compose on Android, SwiftUI on iOS, Room + Koin.</sub>

![](https://img.shields.io/github/stars/Alims-Repo/TaskFlow?style=flat-square&label=&color=7F52FF&labelColor=1a1b27)

</td>
</tr>
</table>

<details>
<summary><b>🔍 Experiments & older work</b></summary>

<br/>

- **[RefactoringPlan](https://github.com/Alims-Repo/RefactoringPlan)** — structured modernisation plan for a seven-year-old legacy Android codebase: architecture, dependency debt, performance
- **[Scrapper](https://github.com/Alims-Repo/Scrapper)** — video URL extraction from TikTok, Facebook, Instagram and X
- **[SmolChat-Android](https://github.com/Alims-Repo/SmolChat-Android)** *(fork)* — running GGUF-format SLMs/LLMs fully on-device; my on-device AI sandbox

</details>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0D1117,50:7F52FF,100:0D1117" width="100%"/>

<br/>

# 📊 Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Alims-Repo&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=7F52FF&icon_color=7F52FF&text_color=8B949E&bg_color=00000000" height="165" alt="GitHub stats"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alims-Repo&layout=compact&hide_border=true&langs_count=6&title_color=7F52FF&text_color=8B949E&bg_color=00000000" height="165" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com/?user=Alims-Repo&hide_border=true&ring=7F52FF&fire=7F52FF&currStreakLabel=7F52FF&sideNums=8B949E&sideLabels=8B949E&dates=6E7681&stroke=30363D&background=00000000" height="165" alt="Contribution streak"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alims-Repo/Alims-Repo/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Alims-Repo/Alims-Repo/output/snake.svg"/>
  <img src="https://raw.githubusercontent.com/Alims-Repo/Alims-Repo/output/snake.svg" width="98%" alt="Contribution snake"/>
</picture>

</div>

<br/>

<div align="center">

## 🤝 Let's build something

**Open to freelance work, full-time roles, and open-source collaboration.**

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-7F52FF?style=for-the-badge)](https://alims-repo.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7F52FF?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-alim-monshi-5874511b2/)
[![Email](https://img.shields.io/badge/Email-7F52FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sourav.0.alim@gmail.com)

<sub>⭐ A star on anything useful goes a long way.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:0D1117,50:5B2AB8,100:7F52FF" width="100%"/>

</div>
