# MOS Backup Plus

mos-backup-plus provides a **MOS plugin** for automated backup management of boot,
appdata and libvirt. It is based on the original MOS Backup plugin and can be
installed alongside it (separate plugin ID, paths and settings).

---

## Overview

This repository contains the **MOS plugin implementation**, helper functions,
and configuration files (such as `settings.json`) required to integrate backup
functionality into MOS.

---

## Build & Automation

This repository includes a **GitHub Actions workflow** used to build and package
the plugin for MOS.

The build process is fully automated and produces artifacts that can be
installed through the MOS Hub.

---

## Licensing

The contents of this repository (plugin code, scripts, and configuration)
are licensed under **GPL-3.0**.
