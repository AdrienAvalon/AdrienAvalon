<p align="center">
  <img src="assets/banner.svg" alt="Avalon Network — Systems. Code. Exploration." width="100%">
</p>

<div align="center">

# Adrien Cros · Avalon Network

**I run Linux systems and build the tools I wish I had.**

Rust desktop applications, Ansible automation and self-hosted infrastructure.
Alongside them: experiments with AI agents and an FPS project in Unreal Engine.

[Français](README.md) · [English](README.en.md) · [Projects](#four-projects-to-start-with) · [How I work](#from-everyday-needs-to-code) · [Contact](https://avalon-network.com)

</div>

## Four projects to start with

| Project | Explore |
|---|---|
| [**Avash**](https://github.com/AdrienAvalon/avash) | A desktop application bringing SSH, RDP, VNC and SFTP together.<br>[Download a release](https://github.com/AdrienAvalon/avash/releases/latest) |
| [**SysAdmin-Tools**](https://github.com/AdrienAvalon/SysAdmin-Tools) | Read-only Linux diagnostics with a dedicated SLES 12 SP5 workflow.<br>[Read the guide](https://github.com/AdrienAvalon/SysAdmin-Tools/blob/main/README.en.md#first-diagnosis) |
| [**Destructible FPS**](https://github.com/AdrienAvalon/destructible-fps) | An industrial environment in Unreal, documented with screenshots and video.<br>[Watch the walkthrough](https://github.com/AdrienAvalon/destructible-fps/blob/main/README.en.md#video) |
| [**Avalon Research**](https://github.com/AdrienAvalon/avalon-research) | Independent publications on AI agent memory and architecture.<br>[Browse publications](https://github.com/AdrienAvalon/avalon-research/blob/main/README.en.md#publications) |

## Avash · connect, work, transfer

[![Published release](https://img.shields.io/github/v/release/AdrienAvalon/avash?style=flat-square&label=release&color=8b7cf6)](https://github.com/AdrienAvalon/avash/releases/latest)
[![Avash CI](https://img.shields.io/github/actions/workflow/status/AdrienAvalon/avash/ci.yml?branch=main&style=flat-square&label=CI&logo=github)](https://github.com/AdrienAvalon/avash/actions/workflows/ci.yml)
[![Release downloads](https://img.shields.io/github/downloads/AdrienAvalon/avash/total?style=flat-square&label=downloads&color=45c7a7)](https://github.com/AdrienAvalon/avash/releases)
[![Avash license](https://img.shields.io/github/license/AdrienAvalon/avash?style=flat-square&label=license)](https://github.com/AdrienAvalon/avash/blob/main/LICENSE)

**SSH** terminals, **RDP / VNC** desktops, **SFTP** transfers and tunnels in a
**Rust + Tauri** application that uses your existing OpenSSH configuration.

<a href="https://github.com/AdrienAvalon/avash#avash">
  <img src="https://raw.githubusercontent.com/AdrienAvalon/avash/main/docs/captures/terminal-ssh.png" alt="A real Avash screenshot showing an SSH terminal, saved hosts and connection tools." width="100%">
</a>

[**Explore the application**](https://adrienavalon.github.io/avash/) · [**Install**](https://github.com/AdrienAvalon/avash/blob/main/README.en.md#install) · [Demo](https://github.com/AdrienAvalon/avash#avash) · [Tests and quality](https://github.com/AdrienAvalon/avash/blob/main/docs/qualite.md)

## From everyday needs to code

My focus is making systems administration easier to understand, reproduce and verify.

| Area | How I approach it |
|---|---|
| **Systems and automation** | Describe the desired state in Git, converge with Ansible and verify the observed state |
| **Software tools** | Start with a practical need, document usage and test the important behaviors |
| **Operations** | Connect monitoring, logs and backups to recovery procedures |
| **Experiments** | Show reproducible results and distinguish working features from next steps |

<p>
  <img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&amp;logo=linux&amp;logoColor=FCC624" alt="Linux">
  <img src="https://img.shields.io/badge/Ansible-0D1117?style=flat-square&amp;logo=ansible&amp;logoColor=EE0000" alt="Ansible">
  <img src="https://img.shields.io/badge/Rust-0D1117?style=flat-square&amp;logo=rust&amp;logoColor=DEA584" alt="Rust">
  <img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&amp;logo=python&amp;logoColor=58A6FF" alt="Python">
  <img src="https://img.shields.io/badge/Bash-0D1117?style=flat-square&amp;logo=gnubash&amp;logoColor=4EAA25" alt="Bash">
  <img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&amp;logo=docker&amp;logoColor=2496ED" alt="Docker">
</p>

## Destructible FPS · development in view

A game project in **Unreal Engine 5.8.2**, built around a ruined factory to explore.
The public **Marble Walk** milestone shows a first-person visit in the Linux editor.

<a href="https://github.com/AdrienAvalon/destructible-fps/blob/main/README.en.md#video">
  <img src="https://raw.githubusercontent.com/AdrienAvalon/destructible-fps/main/docs/screenshots/2026-09-08-unreal-marble-overview.png" alt="Native Unreal screenshot: the Marble factory and its ruined courtyard. Follow the link to watch the walkthrough." width="100%">
</a>

[**Watch the video · 32 s**](https://github.com/AdrienAvalon/destructible-fps/blob/main/docs/videos/2026-09-10-marble-walk.mp4) · [Unreal gallery](https://github.com/AdrienAvalon/destructible-fps/blob/main/README.en.md#unreal-screenshots) · [Status and next steps](https://github.com/AdrienAvalon/destructible-fps/blob/main/README.en.md#project-status)

*Editor capture from September 8, 2026. World generated with World Labs / Marble,
rendered with Cesium for Unreal. Destruction and multiplayer still need to be brought
into Unreal; the Rust prototype remains a reference. No public Unreal package is announced.*

## AI · building and questioning

**[Ava](https://github.com/AdrienAvalon/ava/tree/ava-main)** adapts OpenJarvis into a
French-speaking personal assistant: voice, targeted tools, identity and memory.
Available capabilities depend on configured services and granted access.

**[Avalon Research](https://github.com/AdrienAvalon/avalon-research)** brings together
exploratory publications in French and English, with their Zenodo references.
These are independent works; publication does not establish independent scientific validation.

<details>
<summary><strong>Other tools and early projects</strong></summary>

| Project | Scope |
|---|---|
| [AVALON-terminal](https://github.com/AdrienAvalon/AVALON-terminal) | Personal Zsh/tmux setup for Debian/Ubuntu; review the installation before applying it |
| [Shell-Linux-update](https://github.com/AdrienAvalon/Shell-Linux-update) | Small historical APT script with confirmation |
| [secu](https://github.com/AdrienAvalon/secu) | Bash exercise covering Unix permissions and text processing |
| [server-status-checker](https://github.com/AdrienAvalon/server-status-checker) | Vue/Node.js network reachability dashboard for isolated experiments |
| [VSCode-chatgpt](https://github.com/AdrienAvalon/VSCode-chatgpt) | Historical API integration experiment, not distributed as a finished extension |

Each README explains its project's requirements and current state.
Forks of upstream dependencies and tools also support contributions and experiments.

</details>

---

**An idea, usage feedback or a contribution?** Open an issue in the relevant project
to keep the technical context together. To contact me:
[**Avalon Network**](https://avalon-network.com).

*Each project retains its own license. [Rights for this profile presentation](RIGHTS.md#english).*
