<div align="center">

<img src="/banner.svg" alt="Vũ Cao Nguyên — Mobile Engineer, Security-minded" width="100%"/>

<br/>

<a href="https://nguyencaovu2007-design.github.io/vucaonguyeniosengineer/"><img src="https://img.shields.io/badge/PORTFOLIO-6c5ce7?style=for-the-badge&logo=safari&logoColor=white"/></a>
<a href="mailto:nguyencaovu2007@gmail.com"><img src="https://img.shields.io/badge/CONTACT-0f0c29?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/karsirdev?tab=repositories"><img src="https://img.shields.io/badge/REPOSITORIES-302b63?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/OPEN_TO-INTERNSHIP-22c55e?style=for-the-badge"/>

</div>

<br/>

```swift
// profile.swift
struct Engineer {
    let name       = "Vũ Cao Nguyên"
    let university = "PTIT — Software Engineering (Year 2)"
    let location   = "Ho Chi Minh City, Vietnam"
    let craft      = ["iOS", "Android"]
    let security   = ["Cryptography", "Mobile Security"]
    let mission    = "Build native apps that are fast, beautiful — and secure by design."
    let status     = "Seeking Mobile Internship · iOS / Android"
}
```

## Tech Stack

<div align="center">

![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

| Domain | Details |
|:--|:--|
| **iOS** | Swift · SwiftUI · MVVM |
| **Android** | Kotlin · Jetpack Compose · Material Design 3 |
| **Fundamentals** | C++ · OOP · Data Structures & Algorithms |
| **Design & Workflow** | Figma · Git · Conventional Commits |

## Featured Project — SavingsBook

> Personal finance & savings tracker. One product, two native apps, one design language.

<table>
<tr>
<td width="50%" valign="top">

### [SavingsBook-iOS](https://github.com/karsirdev/SavingsBook-iOS)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white) ![Status](https://img.shields.io/badge/in_progress-a78bfa?style=flat-square)

- Figma-first **dual-theme** system (Light / Dark)
- Custom **design-token** layer
- **MVVM**, feature-based structure
- Auth flow: `Welcome → Login → Register → OTP`
- Reusable `PrimaryButton`, `SBTextField`, `PasswordField`

</td>
<td width="50%" valign="top">

### [SavingsBook-Android](https://github.com/karsirdev/SavingsBook-Android)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Compose](https://img.shields.io/badge/Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Status](https://img.shields.io/badge/in_progress-a78bfa?style=flat-square)

- **Material Design 3**, adaptive theming
- **MVVM** on Jetpack Compose
- Same UX as iOS, adapted to Android conventions
- `WelcomeScreen` ✓ · `LoginScreen` _(building)_
- Idiomatic Kotlin from day one

</td>
</tr>
</table>

```mermaid
flowchart LR
    F[Figma Design System] --> T[Design Tokens]
    T --> I[iOS · SwiftUI]
    T --> A[Android · Compose]
    I --> VM1[View → ViewModel → Model]
    A --> VM2[Composable → ViewModel → Model]
```

## Cybersecurity

Mobile apps handle real user data — especially finance apps. I'm building security knowledge alongside my mobile skills, starting from **cryptography** and moving toward application security.

<table>
<tr>
<td width="50%" valign="top">

**Learning track**
- Networking fundamentals
- Linux & command line
- Python for security
- Cryptography _(current focus)_
- Web & mobile application security

</td>
<td width="50%" valign="top">

**Lab & platforms**
- Kali Linux (ARM64, UTM)
- Burp Suite Community
- TryHackMe · PortSwigger Academy
- picoCTF

</td>
</tr>
</table>

**Cryptography in Swift & Kotlin:** AES-256-GCM · SHA-256 · HMAC · RSA · PBKDF2

![Crypto](https://img.shields.io/badge/Cryptography-0f0c29?style=flat-square&logo=letsencrypt&logoColor=22d3ee)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Burp](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

## How I Build

| | |
|:--|:--|
| **Design before code** | Tokens and components first, screens second. |
| **Separation of concerns** | MVVM — views render state, ViewModels own logic. |
| **Platform-native** | Swift written like Swift, Kotlin written like Kotlin. |
| **Secure by default** | Treat user data and credentials as a first-class concern. |
| **Clean history** | Conventional Commits, `git pull --rebase`, reviewable diffs. |

## Roadmap

```diff
+ Console projects shipped         banking_console_kotlin · SwiftOOP
+ SavingsBook designed in Figma    dual-theme system
+ iOS auth flow                    Welcome → Login → OTP
+ Android project initialised      Material 3 + Compose
! Finish SavingsBook-iOS           in progress
! Cryptography fundamentals        in progress
- Release on the App Store
- Android ↔ iOS feature parity
- Mobile internship
```

<div align="center">

<img src="https://github-readme-streak-stats-eight.vercel.app?user=karsirdev&theme=tokyonight&border_radius=10&date_format=j%20M%5B%20Y%5D"/>

<br/>

**Let's build something real — and keep it secure.**
[nguyencaovu2007@gmail.com](mailto:nguyencaovu2007@gmail.com)

</div>
