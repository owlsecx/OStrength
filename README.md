# 🦉 OStrength

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OPass-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OStrength** — Professional Password Strength Analyzer

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OStrength is a professional password-strength analyzer that scores passwords using Shannon entropy and charset analysis while detecting sequential, repeat and keyboard patterns. It normalizes leetspeak, checks against a 500+ common-password list, and estimates crack time for both online and offline GPU attacks. A built-in generator, batch mode and export to TXT/JSON/CSV/HTML round out the desktop application.

---

## ✨ Features


- Shannon-entropy and charset-size analysis with a live, colour-coded strength meter
- Sequential, repeat and keyboard-pattern detection plus leetspeak normalization
- Extended common-password wordlist (500+) for dictionary checks
- Crack-time estimates for online and offline GPU attack scenarios
- Configurable password generator and batch (multi-line) analysis mode
- Export results as TXT, JSON, CSV or HTML; configurable minimum length (8-32)

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OStrength
./OStrength --self-test
./OStrength --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, bundled CPython version, and every bundled library with its exact
  version and license. Feed it to Grype, Trivy or Dependency-Track to audit
  our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

**No telemetry, no analytics, no licence check-in.** This tool does not phone
home. Verify that claim yourself:

```bash
sudo strace -f -e trace=network ./OStrength --help   # watch every network call
firejail --net=none ./OStrength --help               # deny the network entirely
```

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)
