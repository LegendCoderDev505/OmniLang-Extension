# OmniLang Framework

**OmniLang Framework** provides first-class syntax highlighting, language configuration, and grammar support for the **OmniLang** programming language inside Visual Studio Code. It is designed to be the official development environment enhancement for OmniLang, the core language of the **OmniFrame** platform.

---

## 🌐 What is OmniLang?

**OmniLang** is a next-generation, modular programming language designed by [LegendCoderDev] with simplicity, readability, and power in mind. It is used as the native language for the **NSV Platform**, and it enables fast development across diverse domains like:

- **AI & Automation**
- **Web Applications**
- **Security & Government Tools**
- **UI/UX Design**
- **Scripting & Scheduled Tasks**
- **Core Application Logic**

### ✨ OmniLang Highlights

- **Indentation-based structure** (like Python)
- **Module-first philosophy** using `namespace` as the primary declaration
- **Keyword categories** by domain
- Built-in support for:
  - Code and natural language handling
  - Markdown rendering
  - Plugin/Skill extensibility
  - Chain-of-Thought reasoning logic (CoT Engine)
- Designed to power intelligent systems like your personal assistant: **Yoen Robotic**

---

## 🧠 Keyword Categories

OmniLang separates keywords into distinct functional categories:

### 🔷 AI
```omni
Model, train, predict
```

### 🖥️ Design (UI)
```omni
Window, Label, Input, Button, onClick, onLoad
```

### 🌍 Web
```omni
Route, Controller, View, method
```

### 🛠️ Script
```omni
Task, run, schedule, trigger
```

### 🧱 Core
```omni
Function, DataStore, plugin, config
```

### 🌐 Universal
```omni
using, namespace, package
```

These categories give OmniLang a high degree of clarity, structure, and intent, perfect for domain-specific projects or full-stack application development.

---

## 📁 File Extension

OmniLang files use the `.omni` extension.

---

## 🚀 Features in This Extension

- ✅ Syntax highlighting for `.omni` files
- ✅ Language grammar integration with `TextMate`
- ✅ Language configuration for indentation and comments
- ✅ Support for VS Code language services scaffolding

---

## 📦 Installation

You can install this extension manually or via a marketplace (such as Open VSX) once published.

```bash
vsce package
code --install-extension omnilang-framework-0.0.1.vsix
```

Or, install it from [Open VSX](https://open-vsx.org/) once available.

---

## 🛠️ Development Notes

This package uses `vsce` for packaging and intentionally skips prepublish logic to simplify development:

```json
"scripts": {
  "package": "vsce package --no-dependencies --baseContentUrl https://open-vsx.org --baseImagesUrl https://open-vsx.org",
  "vscode:prepublish": "echo \"Skipping prepublish\""
}
```

---

## 🧠 Future Plans

The OmniLang Framework will continue to evolve alongside:

- **OmniLang Compiler**
- **OmniLang Runtime**
- **OmniLang VS Code Extension (LSP + IntelliSense)**
- **OmniLang AI Integration (Yoen Robotic / TT# Engine)**
- **OmniFrame and NSV Developer Platform**

Stay tuned for more advanced capabilities as the framework becomes the foundation for intelligent and autonomous systems.

---

## 📜 License

MIT © LegendCoderDev

---

## 🙌 Credits

Crafted with vision and purpose by **Alex** (LegendCoderDev), creator of OmniLang, OmniFrame, and NSV Platform.
