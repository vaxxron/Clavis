<p align="right">
  <sub><a href="../README.md">Русский</a> · English</sub>
</p>

<div align="center">
  <br />
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo_full.svg" />
    <source media="(prefers-color-scheme: light)" srcset="assets/logo_full_dark.svg" />
    <img width="210" alt="Clavis" src="assets/logo_full.svg" />
  </picture>

  <br /><br />

  <p>
    <strong>Your servers. Your keys. Your control.</strong><br />
    A local-first SSH client for Windows: terminal, SFTP, keys, and tunnels in one window.
  </p>

  <p>
    <a href="https://github.com/vaxxron/Clavis/releases/latest"><strong>Download v1.1.0 Beta</strong></a>
    &nbsp;·&nbsp;
    <a href="#features">Features</a>
    &nbsp;·&nbsp;
    <a href="#security">Security</a>
    &nbsp;·&nbsp;
    <a href="#installation">Install</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/vaxxron/Clavis/issues">Issues</a>
  </p>

  <br />

  <img width="100%" alt="Clavis interface" src="assets/3dinterface.png" />
</div>

<br />

**Clavis** is a lightweight **local-first** SSH client. Your hosts, passwords, and keys stay encrypted on your own machine — no cloud sync, accounts, or telemetry.

<br />

## Features

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>60 FPS Terminal</strong><br />
      <sub>Tabs, 256 colors, and throttled buffering so heavy logs never freeze the UI.</sub>
    </td>
    <td width="50%" valign="top">
      <strong>SFTP File Manager</strong><br />
      <sub>Background transfers without blocking the shell, previews, and instant cancellation.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Tunnels &amp; OpenSSH</strong><br />
      <sub>One-click port forwarding and auto-discovery of hosts and keys from <code>~/.ssh/</code>.</sub>
    </td>
    <td width="50%" valign="top">
      <strong>aaPanel Integration</strong><br />
      <sub>Access your web panel over an automatic local SSH tunnel without exposing ports.</sub>
    </td>
  </tr>
</table>

<br />

## Security

* **Local Vault:** `Argon2id` + `AES-256-GCM` with AAD integrity verification.
* **MITM Protection:** `known_hosts` fingerprint verification on connect.
* **Offline-first:** zero trackers, analytics, or external cloud dependencies.

<br />

## Installation

For **Windows 10 / 11 (x64)**:

1. Open [GitHub Releases](https://github.com/vaxxron/Clavis/releases/latest) and download `ClavisSetup_Beta_v1.1.0.exe`.
2. Run the installer — no extra dependencies required.

Found a bug or have an idea? Open an [Issue](https://github.com/vaxxron/Clavis/issues).

---

<div align="center">
  <sub>Windows 10 / 11 (x64) · v1.1.0 Beta · <a href="https://github.com/vaxxron/Clavis">vaxxron/Clavis</a></sub>
</div>
