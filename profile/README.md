<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/UNCACHED-LOGO-LIGHT-NOBG.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/UNCACHED-LOGO-DARK-NOBG.svg">
    <img alt="Uncached Logo" src="assets/UNCACHED-LOGO-LIGHT-NOBG.svg" width="380">
  </picture>
</p>

<p align="center">
  <strong>Reclaim disk space from disposable build artifacts.</strong>
</p>

<p align="center">
  <a href="https://uncached.app"><img src="https://img.shields.io/badge/Website-uncached.app-b9d98d?style=for-the-badge&logoColor=101311" alt="Website" /></a>
  <img src="https://img.shields.io/badge/Privacy-100%25_Local-101311?style=for-the-badge" alt="100% Local" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />
</p>

---

## <img src="assets/icons/zap.svg" width="22" height="22" /> Overview

**Uncached** is a lightweight, safety-first desktop application designed for software developers to quickly find and clear disposable build artifacts and caches (`node_modules`, Rust `target/`, `.gradle/`, `.next/`, `.turbo/`, `__pycache__`) across their workspaces — freeing up tens of gigabytes without manual hunting through folders.

---

## <img src="assets/icons/sparkles.svg" width="22" height="22" /> Features & Highlights

<table>
  <tr>
    <td width="30" align="center" valign="top"><img src="assets/icons/check-circle.svg" width="18" height="18" /></td>
    <td><strong>Blazing Fast Scanning</strong>: Instantly scans tens of thousands of project directories in seconds.</td>
  </tr>
  <tr>
    <td width="30" align="center" valign="top"><img src="assets/icons/check-circle.svg" width="18" height="18" /></td>
    <td><strong>Safety-First Cleanup</strong>: Reclaims space by moving disposable directories to the native OS Recycle Bin/Trash by default.</td>
  </tr>
  <tr>
    <td width="30" align="center" valign="top"><img src="assets/icons/check-circle.svg" width="18" height="18" /></td>
    <td><strong>100% Local & Private</strong>: Zero telemetry, zero analytics, zero cloud uploads. Your filesystem stays completely on your device.</td>
  </tr>
  <tr>
    <td width="30" align="center" valign="top"><img src="assets/icons/check-circle.svg" width="18" height="18" /></td>
    <td><strong>Calm Developer Interface</strong>: A quiet, dark aesthetic with exact byte counts and precise path confirmation.</td>
  </tr>
</table>

---

## <img src="assets/icons/box.svg" width="22" height="22" /> Supported Ecosystems

| Ecosystem | Target Directory | Description | Default Action |
| :--- | :--- | :--- | :---: |
| **Node.js / Web** | `node_modules` | Package dependencies cache | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |
| **Rust / Cargo** | `target/` | Compiled Rust binaries and intermediate build artifacts | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |
| **Android / Java** | `.gradle/` | Gradle build cache and wrapper dependencies | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |
| **Next.js** | `.next/` | Next.js build cache and static output | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |
| **Turborepo** | `.turbo/` | Turborepo build cache | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |
| **Python** | `__pycache__`, `.pytest_cache`, `.mypy_cache` | Bytecode, test, and type-check caches | <img src="assets/icons/check-circle.svg" width="16" height="16" /> Recycle Bin |

---

## <img src="assets/icons/shield.svg" width="22" height="22" /> Safety Guarantees

> **Safety First:**
> - **Recycle Bin Default**: All cleanup operations default to moving target folders to your operating system's Recycle Bin or Trash.
> - **Strict Path Scoping**: Only disposable targets identified during your active scan session can be cleared.
> - **Source Code Protection**: Source code, git history, and non-regenerable files are strictly untouched.

---

## <img src="assets/icons/globe.svg" width="22" height="22" /> Links & Resources

- **Website & Documentation**: [uncached.app](https://uncached.app)
- **Organization**: [github.com/uncached-app](https://github.com/uncached-app)
- **License**: MIT
