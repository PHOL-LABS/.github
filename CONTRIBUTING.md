# 🧩 Contributing to PHOL-LABS Kft

First off — thank you for your interest in contributing to **PHOL-LABS** projects!  
Whether you’re fixing a bug, improving documentation, designing hardware, or adding new firmware features — your help makes our ecosystem stronger.

---

## ⚙️ How to Contribute

### 🐞 Reporting Issues
1. Use the **Issues** tab in the respective repository.
2. Provide a **clear title** and **detailed description** of the problem.
3. Include:
   - Expected vs. actual behavior  
   - Steps to reproduce (if applicable)  
   - Hardware version / firmware commit / environment info  
   - Screenshots, logs, or serial output if available  

Before opening a new issue, please **check existing issues** to avoid duplicates.

---

### 💡 Suggesting Enhancements
We love new ideas — for hardware, firmware, or tooling!

When suggesting improvements:
- Explain the motivation behind the idea (what problem it solves).
- Suggest potential approaches.
- Link to any references or prototypes you have.

If it’s a large feature, please open a **discussion** before submitting a PR.

---

### 🧰 Development Setup

Our projects typically fall into one of these categories:

| Area | Tech Stack | Notes |
|------|-------------|-------|
| **Firmware** | ESP-IDF / STM32 HAL / FreeRTOS / MicroPython | Use project’s README for build instructions. |
| **Hardware** | KiCAD / EasyEDA / 3D CAD (Fusion, FreeCAD) | Keep schematic sources clean, consistent, and versioned. |
| **Web / Tools** | React / Vite / Svelte / Python / Docker | Use `dev` branch for UI or backend changes. |

> 🧠 Tip: Each repository includes its own setup guide — follow that for dependencies and environment preparation.

---

### 🧪 Submitting a Pull Request

1. **Fork** the repository.  
2. Create a **feature branch**:  
   ```bash
   git checkout -b feature/my-improvement
