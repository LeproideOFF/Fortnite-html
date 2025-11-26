# 🏝️ Fortnite Web V7 - Ultimate Edition

![Version](https://img.shields.io/badge/version-7.0-blueviolet)
![Status](https://img.shields.io/badge/status-playable-brightgreen)
![Engine](https://img.shields.io/badge/engine-Three.js-white)
![Multiplayer](https://img.shields.io/badge/p2p-PeerJS-orange)

> **Un clone de Battle Royale complet, multijoueur et 3D, contenu dans un seul fichier HTML.** > *Pas d'installation, pas de serveur lourd, juste du fun.*

---

## 📸 Aperçu

Ce projet est une expérimentation technique visant à recréer les mécaniques fondamentales de Fortnite (Construction, Tir, Zone, Multijoueur) en utilisant uniquement des technologies Web standards.

## ✨ Fonctionnalités Principales

| Catégorie | Détails |
| :--- | :--- |
| **🎮 Modes de Jeu** | **Solo** (vs 30 Bots IA) & **Multijoueur** (1v1 via Peer-to-Peer). |
| **🧱 Construction** | Système de grille intelligent. Posez des **Murs** et des **Escaliers** qui s'adaptent au terrain. |
| **🔫 Combat** | Hitscan, recul visuel de l'arme, marqueurs de dégâts et Kill Feed. |
| **🌪️ La Zone** | Une tempête dynamique qui rétrécit toutes les 60 secondes. |
| **💾 Progression** | Sauvegarde locale (LocalStorage) de l'XP, du niveau et des Skins débloqués. |
| **🎒 Personnalisation** | Casier fonctionnel avec skins débloquables via le **Passe de Combat**. |
| **🗺️ Interface** | Minimap en temps réel, ATH complet (Santé, Matériaux, Munitions). |

---

## 🚀 Comment Jouer ?

### Option 1 : En local (Recommandé pour tester)
1. Téléchargez le fichier `fortnite_v7.html` (ou `index.html`).
2. Ouvrez-le simplement avec **Google Chrome**, **Firefox** ou **Edge**.
3. Cliquez sur l'écran pour capturer la souris.

### Option 2 : Héberger sur GitHub Pages
1. Nommez votre fichier principal `index.html`.
2. Activez **GitHub Pages** dans les paramètres de votre dépôt.
3. Envoyez le lien à vos amis pour jouer en mode Multijoueur !

---

## 🕹️ Contrôles

| Action | Touche (Clavier) | Souris |
| :--- | :---: | :---: |
| **Se Déplacer** | `Z` `Q` `S` `D` | - |
| **Sauter / Parachute** | `ESPACE` | - |
| **Tirer / Récolter** | - | `Clic Gauche` |
| **Construire Mur** | `C` | - |
| **Construire Escalier** | `V` | - |
| **Viser (Caméra)** | - | `Mouvement Souris` |

---

## 🌐 Guide du Multijoueur (P2P)

Ce jeu utilise **PeerJS** pour connecter deux navigateurs directement sans passer par un serveur de jeu.

1.  **L'Hôte (Joueur 1) :**
    * Sélectionne "MULTIJOUEUR" dans le menu.
    * Clique sur `CRÉER (HOST)`.
    * Copie l'ID jaune qui apparaît (ex: `e43-a2...`).
    * Envoie cet ID à son ami (Discord, SMS, etc.).

2.  **L'Invité (Joueur 2) :**
    * Lance le jeu de son côté.
    * Colle l'ID dans la case "ID de l'ami".
    * Clique sur `REJOINDRE`.

> **Note :** Certains réseaux (écoles, entreprises) peuvent bloquer les connexions P2P. Si la connexion échoue, essayez en 4G ou sur un réseau domestique.

---

## 🛠️ Technologies Utilisées

* **HTML5 / CSS3** : Interface utilisateur (HUD, Menus) et Canvas.
* **[Three.js](https://threejs.org/)** : Moteur de rendu 3D, géométrie, lumières.
* **[PeerJS](https://peerjs.com/)** : Gestion du réseau WebRTC pour le multijoueur.
* **PointerLockControls** : Gestion de la caméra FPS.

---

## 🔮 Futures Mises à Jour (Idées)

- [ ] Ajout de sons (Tirs, Pas, Construction).
- [ ] Plus de types de constructions (Sol, Toit).
- [ ] Système d'inventaire avec plusieurs armes (Pompe, Sniper).
- [ ] Optimisation des collisions (Physique Cannon.js).

---

**Avertissement :** *Ce projet est un fan-game éducatif et n'est pas affilié à Epic Games.*

Made with ❤️ by [Votre Pseudo]
