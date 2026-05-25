# Aethelium Demos

A collection of lightweight demonstration projects and reference implementations built using the **Aethelium** language and its ecosystem.

These projects serve as a sandbox for exploring Aethelium's capabilities, ranging from bare-metal firmware manipulation and UEFI bootloader design to native Windows system application development using the Aura & Flux UI framework.

## 📁 Repository Contents

*   **Bare-metal/UEFI**: Minimalist firmware and boot-time graphics demonstrations.
*   **Windows**: Native GUI utilities, system monitors, and utility tools utilizing direct NT system calls via `AELibrary`.

## 🛠 Prerequisites

Ensure you have the Aethelium compiler (`aethelc`) installed and the `AELibraryPATH` environment variable configured:

```powershell
# PowerShell example
[Environment]::SetEnvironmentVariable("AELibraryPATH", "C:\Path\To\Your\AELibrary", "User")
```

## ⚖️ Usage Guidelines & Scope

This repository is curated for **learning and demonstration purposes**. 

*   **Scope**: These demos are intended to showcase language features, pattern adoption, and interface integration. They are structured to be concise, readable, and highly focused on specific API/ABI paradigms.
*   **Production Projects**: If you are developing large-scale, production-ready applications or complex proprietary systems, we encourage you to maintain these in your own dedicated repositories. This allows you to manage your own dependency versioning, CI/CD pipelines, and licensing strategies tailored to your specific product roadmap.

## 📄 License

All code in this repository is distributed under the **MIT License**. You are free to incorporate these patterns and code snippets into your own projects.