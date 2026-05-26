# Formation Thermographie par Drone — Dronexperts

Cours en ligne d'initiation à la thermographie par drone, format **2 jours présentiel** (14h pédagogiques), destiné aux télépilotes certifiés novices en thermographie.

**Matériel cible** : DJI Mavic 3T &amp; DJI Matrice 4T.

## 🌐 Accès en ligne

[formation-thermographie](https://dronexperts33.github.io/formation-thermographie/index-formation.html) *(GitHub Pages — à activer)*

## 📚 Contenu

| Demi-journée | Module | Slides |
|---|---|---|
| **J1 Matin** | Fondamentaux IR &amp; thermique du bâtiment | ~28 |
| **J1 Après-midi** | Matériel DJI &amp; préparation mission | ~30 |
| **J2 Matin** | Méthodologie &amp; cas d'usage | ~34 |
| **J2 Après-midi** | Post-traitement, normes &amp; rapport | ~36 |
| QCM J1 | Validation acquis fondamentaux | 10 questions |
| QCM J2 | Validation acquis méthodologie | 10 questions |

## 🛠 Stack technique

- **Reveal.js 5.1.0** via CDN jsDelivr
- **Thème Dronexperts** custom (charte v2.3, police Inter, couleur primaire `#0E74DA`)
- **HTML statique** — pas de build, déploiement direct GitHub Pages

## 📁 Structure

```
template/
├── index.html                       Démo des 11 types de slides
├── index-formation.html             Sommaire 2 jours (page d'accueil)
├── livret-instructeur.html          Livret d'accueil (imprimable A4)
├── formation-jour1-matin.html       J1 AM : Fondamentaux IR
├── formation-jour1-aprem.html       J1 PM : Matériel DJI & préparation
├── formation-jour2-matin.html       J2 AM : Méthodologie & cas d'usage
├── formation-jour2-aprem.html       J2 PM : Post-traitement & rapport
├── formation-qcm-j1.html            QCM Jour 1
├── formation-qcm-j2.html            QCM Jour 2
├── css/dronexperts-theme.css        Thème CSS partagé
├── assets/
│   ├── img/logo-dronexperts.svg     Logo Dronexperts (SVG)
│   └── docs/                        Ressources téléchargeables (PDF, DOCX)
├── CLAUDE.md                        Règles de production (accents, charte)
└── README.md                        Ce fichier
```

## 📄 Ressources annexes (téléchargeables)

- Plan de rapport thermographique (modèle vierge)
- Tableau des émissivités des matériaux
- Aide-mémoire conductivité thermique
- Préparer une intervention sur site (check-list)
- Modèle de devis type
- Modèles d'autorisations (décollage + prise de vue)

## 📐 Normes citées

- **NF EN 13187** — Méthode qualitative bâtiment
- **APSAD D19** — Prévention incendie / électrique
- **NF A09-400** — Vocabulaire thermographie IR

## 🚀 Lancer en local

```bash
# Ouvrir directement dans un navigateur
open index-formation.html

# Ou avec un serveur HTTP simple
python3 -m http.server 8000
# Puis http://localhost:8000/index-formation.html
```

## 📜 Licence

© 2026 Dronexperts — Tous droits réservés.
