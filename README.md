<p align="center">
  <img src="assets/banner.svg" alt="Avalon Network — Systems. Code. Exploration." width="100%">
</p>

<div align="center">

# Adrien Cros · Avalon Network

**J’administre des systèmes Linux et je construis les outils qui me manquent.**

Applications de bureau en Rust, automatisation avec Ansible, infrastructure auto-hébergée.
Et, pour explorer d’autres pistes : agents IA et développement d’un FPS sous Unreal Engine.

[Français](README.md) · [English](README.en.md) · [Projets](#quatre-projets-pour-commencer) · [Ma démarche](#du-terrain-au-code) · [Contact](https://avalon-network.com)

</div>

## Quatre projets pour commencer

| Projet | À découvrir |
|---|---|
| [**Avash**](https://github.com/AdrienAvalon/avash) | Une application de bureau pour réunir SSH, RDP, VNC et SFTP.<br>[Télécharger une version](https://github.com/AdrienAvalon/avash/releases/latest) |
| [**SysAdmin-Tools**](https://github.com/AdrienAvalon/SysAdmin-Tools) | Un diagnostic Linux en lecture seule, avec un parcours dédié à SLES 12 SP5.<br>[Lire le guide](https://github.com/AdrienAvalon/SysAdmin-Tools#premier-diagnostic) |
| [**Destructible FPS**](https://github.com/AdrienAvalon/destructible-fps) | Le développement d’un environnement industriel sous Unreal, montré en captures et en vidéo.<br>[Voir la visite](https://github.com/AdrienAvalon/destructible-fps#vidéo) |
| [**Avalon Research**](https://github.com/AdrienAvalon/avalon-research) | Des publications indépendantes sur la mémoire et les architectures des agents IA.<br>[Parcourir les publications](https://github.com/AdrienAvalon/avalon-research#publications) |

## Avash · se connecter, travailler, transférer

[![Version publiée](https://img.shields.io/github/v/release/AdrienAvalon/avash?style=flat-square&label=version&color=8b7cf6)](https://github.com/AdrienAvalon/avash/releases/latest)
[![CI Avash](https://img.shields.io/github/actions/workflow/status/AdrienAvalon/avash/ci.yml?branch=main&style=flat-square&label=CI&logo=github)](https://github.com/AdrienAvalon/avash/actions/workflows/ci.yml)
[![Téléchargements des versions](https://img.shields.io/github/downloads/AdrienAvalon/avash/total?style=flat-square&label=téléchargements&color=45c7a7)](https://github.com/AdrienAvalon/avash/releases)
[![Licence Avash](https://img.shields.io/github/license/AdrienAvalon/avash?style=flat-square&label=licence)](https://github.com/AdrienAvalon/avash/blob/main/LICENSE)

Terminaux **SSH**, bureaux **RDP / VNC**, transferts **SFTP** et tunnels dans une
application **Rust + Tauri**, qui reprend votre configuration OpenSSH.

<a href="https://github.com/AdrienAvalon/avash#avash">
  <img src="https://raw.githubusercontent.com/AdrienAvalon/avash/main/docs/captures/terminal-ssh.png" alt="Capture réelle d’Avash : un terminal SSH, les hôtes enregistrés et les outils de connexion." width="100%">
</a>

[**Découvrir l’application**](https://adrienavalon.github.io/avash/) · [**Installer**](https://github.com/AdrienAvalon/avash#installation) · [Démonstration](https://github.com/AdrienAvalon/avash#avash) · [Tests et qualité](https://github.com/AdrienAvalon/avash/blob/main/docs/qualite.md)

## Du terrain au code

Mon fil conducteur : rendre l’administration plus lisible, reproductible et vérifiable.

| Domaine | Ma façon de travailler |
|---|---|
| **Systèmes et automatisation** | Décrire l’état attendu dans Git, converger avec Ansible et vérifier l’état observé |
| **Outils logiciels** | Partir d’un besoin concret, documenter l’usage et tester les comportements importants |
| **Exploitation** | Relier supervision, journaux et sauvegardes à des procédures de reprise |
| **Expérimentation** | Montrer un résultat reproductible et distinguer ce qui fonctionne des prochaines étapes |

<p>
  <img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&amp;logo=linux&amp;logoColor=FCC624" alt="Linux">
  <img src="https://img.shields.io/badge/Ansible-0D1117?style=flat-square&amp;logo=ansible&amp;logoColor=EE0000" alt="Ansible">
  <img src="https://img.shields.io/badge/Rust-0D1117?style=flat-square&amp;logo=rust&amp;logoColor=DEA584" alt="Rust">
  <img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&amp;logo=python&amp;logoColor=58A6FF" alt="Python">
  <img src="https://img.shields.io/badge/Bash-0D1117?style=flat-square&amp;logo=gnubash&amp;logoColor=4EAA25" alt="Bash">
  <img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&amp;logo=docker&amp;logoColor=2496ED" alt="Docker">
</p>

## Destructible FPS · un chantier visible

Un projet de jeu sous **Unreal Engine 5.8.2**, avec une usine en ruine à parcourir.
Le jalon public **Marble Walk** montre une visite en première personne dans l’éditeur Linux.

<a href="https://github.com/AdrienAvalon/destructible-fps#vidéo">
  <img src="https://raw.githubusercontent.com/AdrienAvalon/destructible-fps/main/docs/screenshots/2026-09-08-unreal-marble-overview.png" alt="Capture native Unreal : l’usine Marble et sa cour en ruine. Cliquer pour découvrir la vidéo de la visite." width="100%">
</a>

[**Voir la vidéo · 32 s**](https://github.com/AdrienAvalon/destructible-fps/blob/main/docs/videos/2026-09-10-marble-walk.mp4) · [Galerie Unreal](https://github.com/AdrienAvalon/destructible-fps#captures-unreal) · [État et prochaines étapes](https://github.com/AdrienAvalon/destructible-fps#état-du-projet)

*Capture de l’éditeur du 8 septembre 2026. Monde généré avec World Labs / Marble,
rendu avec Cesium for Unreal. La destruction et le multijoueur restent à porter dans
Unreal ; le prototype Rust est conservé comme référence. Aucun package Unreal public n’est annoncé.*

## IA · construire et questionner

**[Ava](https://github.com/AdrienAvalon/ava/tree/ava-main)** adapte OpenJarvis à un
assistant personnel francophone : voix, outils ciblés et travail sur l’identité et
la mémoire. Les capacités disponibles dépendent des services configurés et des accès accordés.

**[Avalon Research](https://github.com/AdrienAvalon/avalon-research)** rassemble les
publications exploratoires, en français et en anglais, avec leurs références Zenodo.
Ce sont des travaux indépendants ; leur publication ne constitue pas une validation scientifique indépendante.

<details>
<summary><strong>Autres outils et premiers projets</strong></summary>

| Projet | Périmètre |
|---|---|
| [AVALON-terminal](https://github.com/AdrienAvalon/AVALON-terminal) | Configuration personnelle Zsh/tmux pour Debian/Ubuntu ; installation à examiner avant application |
| [Shell-Linux-update](https://github.com/AdrienAvalon/Shell-Linux-update) | Petit script APT historique avec confirmation |
| [secu](https://github.com/AdrienAvalon/secu) | Exercice Bash sur les permissions Unix et le traitement de texte |
| [server-status-checker](https://github.com/AdrienAvalon/server-status-checker) | Tableau de bord Vue/Node.js de joignabilité réseau, destiné aux essais isolés |
| [VSCode-chatgpt](https://github.com/AdrienAvalon/VSCode-chatgpt) | Expérimentation historique d’intégration d’une API, non distribuée comme extension aboutie |

Le README de chaque dépôt précise ses conditions d’utilisation et son état.
Les forks de dépendances et d’outils amont servent aussi aux contributions et aux essais.

</details>

---

**Une idée, un retour d’usage ou une contribution ?** Les issues de chaque projet
permettent d’en discuter avec le contexte technique. Pour me contacter :
[**Avalon Network**](https://avalon-network.com).

*Chaque projet conserve sa licence. [Droits de cette présentation](RIGHTS.md).*
