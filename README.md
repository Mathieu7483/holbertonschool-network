<p align="center"\>
<img src="https://github.com/Mathieu7483/Aiko78-Photgraphy/blob/main/img/cr-er-moi-unepage-de-garde-pour-un-projet--network%20(1).png"\>
</p>

---

# Networking Basics #0

## 🌐 Description

Ce projet constitue une introduction aux fondamentaux de l'architecture réseau. Il explore le modèle théorique **OSI** (7 couches) et son application pratique via la suite de protocoles **TCP/IP**. L'objectif est de comprendre l'acheminement des données, de l'impulsion électrique (couche physique) jusqu'à l'application finale (HTTP, SSH), en passant par l'adressage MAC et IP.

## 🎓 Objectifs d'apprentissage

À l'issue de ce module, les concepts suivants sont acquis :

* **Modèle OSI** : Structure conceptuelle et organisation des couches de communication.
* **Topologies de réseau** : Caractéristiques et usages des LAN, WAN et de l'Internet.
* **Adressage** : Distinction entre adresse MAC (physique) et adresse IP (logique, v4 et v6).
* **Protocoles de Transport** : Différences fondamentales entre **TCP** (fiabilité) et **UDP** (vitesse).
* **Ports et Services** : Identification des ports standards (SSH: 22, HTTP: 80, HTTPS: 443).
* **Connectivité** : Utilisation du protocole ICMP (ping) pour le diagnostic réseau.

## 🛠️ Configuration et Contraintes

* **OS** : Ubuntu 22.04 LTS.
* **Langage** : Bash (Shell).
* **Linter** : Conformité stricte à `shellcheck`.
* **Standard** : Tous les fichiers se terminent par une nouvelle ligne et respectent l'entête `#!/usr/bin/env bash`.

## 📂 Structure des Tâches

| Fichier | Sujet | Description |
| --- | --- | --- |
| `0-OSI_model` | Modèle OSI | Définition et hiérarchie du modèle. |
| `1-types_of_network` | Réseaux | Identification LAN vs WAN. |
| `2-MAC_and_IP_address` | Adressage | MAC, IPv4, IPv6 et localhost. |
| `3-UDP_and_TCP` | Transport | Comparaison TCP/UDP et notion de subnet. |
| `4-TCP_and_UDP_ports` | Ports | Numérotation des ports de services critiques. |
| `5-is_the_host_on_the_network` | Diagnostic | Script Bash testant la connectivité d'un hôte. |

## ✒️ Auteur

**Mathieu**

[Mathieu GODALIER](https://github.com/Mathieu7483) - Élève en programmation à la Holberton School

## 🙏 Remerciements

* **Holberton School** : Pour le curriculum et les ressources pédagogiques sur les fondations réseau.
* **Sylvain Kalache** : Pour la conception de ce projet.