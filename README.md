# TSA (AI Engineering OS)

**TSA (TSA-X v7.1)** is a high-performance **AI Engineering Operating System** designed to maximize the effectiveness of AI assistants in software engineering tasks. It implements a strict, contract-driven orchestration layer that ensures technical correctness, simplicity, and extreme token efficiency.

## 🚀 Overview
TSA-X transforms generic LLMs into expert engineering partners. By utilizing a minimal **2-file context system**, it avoids the overhead of full repository scanning while maintaining a deep, persistent memory of the project's state, rules, and history.

## 🛠 Stack
- **Engine**: TSA-X v7.1 (Merged Edition)
- **Framework**: Merged from TSA-X v6.2 + v6.3 + 50-Agreements
- **Memory System**: TSA Persistent Work Memory (`.ai/memory.md`)
- **Compatibility**: Claude, ChatGPT, Gemini, Copilot, Cursor, Windsurf, Aider, and local LLaMA models.

## 📦 Folder Structure
```text
TSA/
├── .ai/
│   └── memory.md           # Persistent project memory (Single Source of Truth)
├── TSA-X-v7.1.md           # Core Operating Rules & Contract
└── README.md               # Project overview (this file)
```

## 📖 Quick Start
1. **Context Loading**: Attach `TSA-X-v7.1.md` and `.ai/memory.md` to your AI assistant session.
2. **AI Initialization**: The assistant will automatically read the `[CONTRACT]` and the `[OPEN ISSUES]` from `memory.md`.
3. **Execution Protocol**:
   - The AI declares its **MODE** (Patch, Feature, Architect, or Review).
   - The AI follows the **Priority Stack**: Correctness > Simplicity > Maintainability.
4. **Memory Synchronization**: After each task, copy the `=== MEMORY UPDATE ===` block from the AI's response and paste it into the `[LOG]` section of `.ai/memory.md`.

## ✨ Key Features
- **Contract-Driven Engineering**: Locked rules that prevent over-engineering and ensure buildable code at all times.
- **Automated Debug Loop**: A self-healing protocol for systematic bug classification and resolution.
- **Advanced Rate Limiting**: Multi-tier protection (Tier 1-5) for external API calls, optimized for paid/free API quotas.
- **Security Checklist**: Mandatory validation for input, secrets, and dependencies.
- **Test-First Requirement**: New logic requires proof-based validation (v7.1 hardening).

## 📄 License
MIT License - Developed by [anoramyid](https://github.com/anoramyid)
