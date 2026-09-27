# 🌹 RoseScript Package Registry (Official Hub)

Welcome to the official central repository and package registry for the **RoseScript** ecosystem! This is an open-source, ultra-fast, and secure hub designed for sharing declarative UI components, system libraries, and hardware-accelerated graphics modules.

Every package published here becomes instantly available to the global community for installation via the `bud` package manager.

---

## 🛡️ Supply Chain Security Core (How it Works)

We do not believe in blind trust. To protect end-users from malicious injections, credential stealers, and destructive code, every single package passes through a **three-tier security pipeline** before going live:

┌────────────────────────────────────────────────────────────────────────┐
│  📥 1. ISOLATED SANDBOX INGESTION                                      │
├────────────────────────────────────────────────────────────────────────┤
│  🔍 2. STATIC VULNERABILITY ANALYZER (BYTECODE SCANNING)               │
│     • Instant blocking of unauthorized hooks like `std::process`       │
│     • Strict prevention of arbitrary filesystem mutations (`rm -rf`)  │
├────────────────────────────────────────────────────────────────────────┤
│  🔏 3. CRYPTOGRAPHIC SIGNING & AUDITING (SHA-256)                      │
│     • Generation of a unique cryptographic tamper-proof fingerprint    │
│     • Hardened protection against "Man-in-the-Middle" (MitM) attacks   │
└────────────────────────────────────────────────────────────────────────┘

---

## 📜 Unified Licensing Policy: Pure MIT Mandate!

To completely eliminate legal friction, copyright trolling, and enterprise adoption barriers, the RoseScript Registry enforces a strict ecosystem rule:

> ⚖️ **Absolutely all packages hosted, distributed, and shared through this registry are automatically published under the terms of the MIT License.**

### What this means for Developers and Authors:
- **Total Commercial Freedom:** You can freely download any component and use it in open-source projects, enterprise applications, closed-source proprietary software, and fast-growing startups without legal overhead.
- **Zero Liability:** The MIT License waives any liability for package maintainers — code is provided "AS IS", completely shielding open-source contributors from legal vulnerabilities.
- **Automated License Injection:** Even if an author forgets to bundle a license file, the `bud` package manager will automatically generate and inject the official MIT license text into the project's local sandbox cache during download.

---

## 🏗️ Repository Architecture (Recommended Package Layout)

To keep the `bud` package manager running like clockwork, the registry is structured into 4 main categories. Adhering to this layout ensures seamless dependency compilation:

Используйте код с осторожностью.📂 packages/┣ 📂 core/         # System extensions, standard math algorithms, core traits┣ 📂 net/          # Network controllers, secure API clients, database hooks┣ 📂 utils/        # String utilities, structural handling, date-time parsing┗ 📂 UI/           # Graphical components, layout engines, interactive panels
### Anatomy of a Perfect Package:
Each library must reside in its designated category directory and contain the following clean structure:
📂 packages/UI/my-awesome-button/┣ 📄 package.json  # Manifest: metadata and hooks┣ 📄 README.md     # Documentation and guides┗ 📂 src/┗ 📄 lib.rose   # Root source entry point
---

## ⚡ Developer Code of Conduct & Ecosystem Stability

Contributors agree to permanent version preservation, a 2-year deprecation lifecycle for inactive modules, and emergency moderation protocols for critical security exploits.

🚀 *Build stunning interfaces, leverage secure open-source code, and reshape the
