# Modula SDUI SDK

**Modula** is a next-generation Server-Driven UI (SDUI) framework that empowers developers to build dynamic, high-performance user interfaces from a single JSON definition. Whether you need deep native integration or maximum code sharing, Modula provides the tools to deliver seamless experiences across Android, iOS, Web, and React Native.

---

## 🚀 Two Powerful Solutions

Modula offers two distinct architectural approaches to suit your project's needs:

### 1. 🧩 KMP Solution (Kotlin Multiplatform)
**"Smart Brain, Native Hands"**

This implementation focuses on shared business logic while using native rendering for the best possible platform-specific performance and feel.

- **80% Shared Logic**: All JSON parsing, data transformations, and business rules are written in a central Kotlin module.
- **20% Mapping Logic**: Native renderers (Jetpack Compose for Android, SwiftUI for iOS) map the shared data into native components.
- **Best For**: Projects requiring a 100% native look and feel with shared complex logic.

👉 [**Explore KMP Solution**](kmp/)

---

### 2. 🎨 CMP Solution (Compose Multiplatform)
**"100% Shared Logic & UI"**

This implementation leverages Jetpack Compose to share not just logic, but also the entire UI layer across all platforms.

- **100% Shared Code**: Both the business logic and the UI implementation (Compose) are shared across Android, iOS, and Web.
- **Truly Write Once, Run Everywhere**: Minimize platform-specific code to almost zero.
- **Best For**: Rapid development, UI consistency across platforms, and teams already familiar with Jetpack Compose.

👉 [**Explore CMP Solution**](cmp/)

---

## 🛠️ Supported Platforms

| Platform | KMP Solution | CMP Solution |
| :--- | :---: | :---: |
| **Android** | ✅ (Compose) | ✅ (Compose) |
| **iOS** | ✅ (SwiftUI) | ✅ (Compose UI) |
| **Web** | ✅ (React/JS) | ✅ (Compose HTML/Canvas) |
| **React Native** | ✅ (Native Bridge) | ✅ (Native Bridge) |

---

## 🌳 Repository Structure

```text
.
├── kmp/       # 80/20 Shared Logic Implementation
└── cmp/       # 100% Shared Logic & UI Implementation
```

---

© 2026 Nostratech Modula. Built with ❤️ for the future of mobile and web development.
