# Kiku (`kiku-package`) Official Documentation / 公式ドキュメント

- **Plugin Name**: `kiku-package`
- **Display Name**: Kiku (聞く) - Zero-Jargon Interview & GO-Sign Gate
- **Version**: `1.0.0`
- **Author / Organization**: **Shinji Sakiyama**
- **Contact & Support**: `shinjisakiyama@gmail.com`

---

## 1. Core Philosophy (設計理念)

1. **Preserve Authentic Source Code (No Code Laundering / コードの原形保持)**
   - Production software must remain in its authentic, native programming language (e.g., Kotlin for Android) so that it compiles, runs, and maintains full architectural and copyright integrity.
2. **Zero Technical Jargon for Humans (専門用語ゼロの対話)**
   - Beginners should never be forced to understand `Kotlin`, `Git`, `PowerShell`, `commit`, `push`, or cryptic terminal prompts. The AI translates all technical concepts into everyday language.
3. **Relentless Listening & Alignment (満足するまで聞きまくる＆答え合わせ)**
   - The agent asks 1–2 simple questions at a time, summarizes the user's intent in plain language, and repeats the alignment check until the user is 100% satisfied.
4. **Strict Pre-Implementation Lock (GOサインが出るまで実装ロック)**
   - No file modifications (`write_file`, `edit_file`) or shell commands (`run_command`) are executed until the user explicitly gives a clear "GO" sign.

---

## 2. Component Architecture (パッケージ構成)

```text
kiku-package/
├── plugin.json                # Antigravity Plugin Manifest
├── assets/
│   └── logo.svg               # High-contrast accessible plugin icon
├── rules/
│   └── AGENTS.md              # Always-on zero-jargon & GO-sign gate rules
├── skills/
│   ├── kiku/
│   │   └── SKILL.md           # /kiku (On-demand interactive interview skill)
│   └── kiku-on/
│       └── SKILL.md           # /kiku-on (Resident always-on interview guard skill)
├── README.md                  # Overview & Quick Start
├── DOCUMENTATION.md           # Full Technical & User Documentation
└── AGREEMENT.md               # End-User License & Anti-Laundering Agreement
```

---

## 3. How to Use (使い方)

1. Open the Antigravity chat input box and press **`/`**.
2. Select **`/kiku`** (for a one-time thorough interview on your current idea) or **`/kiku-on`** (to keep the zero-jargon interview lock active throughout your session).
3. Describe what you want in your own everyday words.
4. Answer the AI's gentle questions until the AI's summary matches your vision 100%.
5. Say **"GO"** (or **「よし、それで進めて！」**) to let the AI implement the genuine code automatically behind the scenes.

---

## 4. Troubleshooting & Support (サポート窓口)

For questions, bug reports, accessibility feedback, or enterprise licensing inquiries, please contact:
- **Primary Contact**: Shinji Sakiyama
- **Email**: [shinjisakiyama@gmail.com](mailto:shinjisakiyama@gmail.com)
- **GitHub Issues**: [https://github.com/shinji5683/kiku-package/issues](https://github.com/shinji5683/kiku-package/issues)
