<!-- ========================================================= -->
<!--             EndSiena Browser — Corporate README           -->
<!-- ========================================================= -->

<div align="center">

<img src="img/EndSiena Browser.png" width="120" alt="EndSiena Logo">  
<!-- Ganti logo setelah upload -->

# 🌀 **EndSiena Browser**
### **Classic Core, Modern Shell — Powered by Neo-Marine Architecture**

---

<p align="center">
  <img src="https://img.shields.io/badge/Status-In_Development-0066ff?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Platform-Android-3ddc84?style=for-the-badge&logo=android" />
  <img src="https://img.shields.io/badge/License-MPL--2.0-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Core-Netscape_5_Legacy-0099ff?style=for-the-badge&logo=mozilla" />
  <img src="https://img.shields.io/badge/Architecture-Hybrid_Cyborg-ff0044?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Community-Open_Source-8e44ad?style=for-the-badge&logo=githubsponsors" />
</p>

---

## 🌟 **Project Vision Statement**

**This project is an early-stage concept — a dream in progress.**  
EndSiena was born from a longing for the early days of the internet:  
a time when browsing felt magical, full of discovery, connection, and childlike curiosity.

I want that feeling to return.  
I want it preserved forever,  
so that future generations can also experience the beauty of classic internet exploration.

EndSiena is my attempt to revive that memory —  
a nostalgic browser built from my past, my hopes, and my desire  
to keep history alive in a fast, simple, classic, and meaningful experience.

I don’t know how long this journey will take —  
but this project is a dream from the heart:  
a dream to revive what once was.

</div>

---


# 📘 **1. Executive Technical Overview**

**Product Name:** EndSiena Browser  
**Codename:** Neo-Marine / EndSiena-Core  
**Product Category:** Hybrid Mobile Browser  
**Platform:** Android  
**Core Philosophy:** *Classic Core, Modern Shell*  

EndSiena Browser is a next-generation hybrid browser engineered by combining modern Android technology with legacy Netscape 5.0 components.  
Built with a unique Cyborg Architecture, EndSiena merges **retro-web structure** and **modern mobile engineering** into a unified system.

---

# 🧬 **2. System Architecture — Corporate Summary**

## **2.1 Shell Layer (Android UI/UX Layer)**  
**Technologies:**
- Kotlin (100%)
- Jetpack Compose (Material 3)
- Android System WebView
- Hilt Dependency Injection
- Retrofit & OkHttp Stack

The Shell functions as the visual and interactive layer responsible for:
- User interface
- AOG dashboard integration
- Extension management
- Git Sync monitoring
- Memory-safe operations

---

## **2.2 Core Layer (Native Data Engine)**  
**Technologies:**  
- C++17  
- ANSI C (Legacy)  
- Based on Netscape 5.0 Source Components  

### **Legacy Modules Preserved**
| Module | Purpose |
|--------|---------|
| NSPR | Runtime abstraction (threads, memory, I/O) |
| DBM | Lightweight key-value index engine |
| zlib | Compression infrastructure |

### **New Corporate Modules**
| Component | Description |
|-----------|-------------|
| `.esn` Binary Packer | Unified offline page format |
| Native Bridge (JNI) | High-speed Kotlin↔C++ pipeline |
| Metadata Engine | Structured JSON metadata generator |
| Image Block Writer | Raw byte-level image storage |

---

# 🚀 **3. Core Features & Engineering Logic**

## **3.1 AOG — Aliansiena Operation Gits**
Enterprise-grade offline capture pipeline.

Transforms any webpage into a **single `.esn` file** with:
- Markdown content  
- Image blocks  
- Metadata header  
- Optional compression  

### **AOG Workflow Pipeline**
1. WebView page-load hook  
2. JS-based HTML harvesting  
3. HTML → Markdown transformation  
4. Asset extraction (byte arrays)  
5. JNI transfer  
6. C++ `.esn` compilation  

---

## **3.2 SmartSearch Engine**
Powered by **Netscape DBM**, chosen for:
- O(1) key lookup  
- Low power consumption  
- Zero SQL overhead  

Search indexing is maintained **fully offline**.

---

## **3.3 ESP Extension Platform**
Custom scripting system for developers.

**Format:** `.esp`  
Includes:
- `manifest.json`  
- `script.js`

Loaded into WebView in a sandbox environment.

---

## **3.4 Git Sync Automation**
Synchronization with GitHub under controlled triggers:
- Device charging  
- WiFi detection  

Ensures minimized CPU, battery, and mobile data usage.

---

# 🗂️ **4. Project Structure Overview**

## **4.1 Native Layer (`/cpp`)**
```
/cpp
 ├── esn_format_manager.cpp
 ├── endsiena_db_bridge.cpp
 └── native_lib.cpp
```

## **4.2 Kotlin Layer (`/app/src/...`)**
```
NativeBridge.kt
MarkdownConverter.kt
GithubRepository.kt
GlassmorphismComponents.kt
```

---

# 🛠️ **5. Technology Index**

| Category | Technology | Purpose |
|----------|-------------|---------|
| Core Language | Kotlin | Application logic & UI |
| System Language | C++17 | Native processing engine |
| Legacy Base | ANSI C | Netscape modules |
| UI Framework | Jetpack Compose | Modern Android UI |
| Data Layer (UI) | Room | History, bookmarks |
| Data Layer (Core) | DBM | Search indexing |
| Build | CMake | Native compilation |

---

# 🗺️ **6. Development Roadmap (Corporate Milestones)**

### **Phase 1 — Core Architecture Setup**  
Legacy integration, native initialization.

### **Phase 2 — `.esn` Format Development**  
Binary writer, metadata pipeline, unit tests.

### **Phase 3 — Shell UI Assembly**  
Glassmorphism design, WebView integration.

### **Phase 4 — Full System Integration**  
AOG activation, Save→Core pipeline.

### **Phase 5 — Cloud & Product Polish**  
GitHub Sync, optimizations, public release preparations.

---

# 📜 **7. Licensing & Branding, Visual Identity**

### **Licenses**
- Mozilla Public License 2.0 (MPL-2.0)  
- Netscape Public License (NPL) for legacy modules  
- MIT License for distribution with mandatory attribution  

### **Branding Notice**
The names:
- **EndSiena**
- **EndSiena Browser**
- **AOG (Aliansiena Operation Gits)**  
are trademarked as part of the EndSiena identity.
- This includes logos and other related branding, which are part of the project’s identity  
Commercial use requires written approval.

---
## **Visual Identity**

EndSiena's visual identity is inspired by strength, resilience, and global connectivity.

- Komodo Dragon — absolute strength and protection
- Globe — borderless digital world
- Blue Fire — rare, clean, intelligent energy

Read the full brand philosophy:
[BRANDING.md](./BRANDING.md)


# 🌐 **8. Official Channels**

| Category | Link |
|---------|------|
| Community (Telegram) | https://t.me/Aliansiena |
| Official Website | https://aliansiena.pages.dev |
| Donation Support | https://linktr.ee/Aliansiena |
| Documentation | *(Reserved — Coming Soon)* |

---

<div align="center">

# 🌀 **EndSiena Browser — Neo-Marine Project**  
### *Classic Core, Modern Shell.*

</div>

---

<div align="center">

### ⚠️ **Corporate Disclaimer — Beta Product**

EndSiena is an active beta-phase project.  
All features, concepts, and implementations are subject to change.  
New systems may be added, revised, or deprecated as development evolves.  
The core vision, however, remains constant.
"I will write the code myself to modify it. Whether I should stick with the old C++ style or use modern C++20, I haven’t decided yet. As for the other parts, I’m still unsure whether to write them in JavaScript or TypeScript—I don’t have any ideas about that yet".

**© EndSiena Project — All Rights Reserved**

</div>


