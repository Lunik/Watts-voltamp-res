<div align="center">

# ⚡ Watts & voltampères

**Démonstrateur interactif : pourquoi votre compteur Linky parle en VA alors que vous payez des kWh.**

[![Démo en ligne](https://img.shields.io/badge/d%C3%A9mo-en%20ligne-2A3DBF?style=for-the-badge)](https://lunik.github.io/Watts-voltamp-res/)
[![Licence CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-21844A?style=for-the-badge)](LICENSE)
![Zéro dépendance](https://img.shields.io/badge/build-aucun-C4501A?style=for-the-badge)

**👉 [lunik.github.io/Watts-voltamp-res](https://lunik.github.io/Watts-voltamp-res/)**

</div>

---

## 🎯 Le propos

Un watt (W), un voltampère (VA), un var… Sur une facture ou un compteur, ces unités se mélangent.
Cette page explique, **de façon visuelle et manipulable**, ce qui les distingue :

- **Puissance active (W, P)** : le travail réellement fourni, celui que vous payez en kWh.
- **Puissance réactive (var, Q)** : l'énergie qui fait des allers-retours sans travailler.
- **Puissance apparente (VA, S)** : ce que le réseau doit transporter, celle qui dimensionne votre abonnement.
- **Puissance déformante (D)** et **facteur de puissance** : l'effet des charges non linéaires.

> Même travail, plus de courant : c'est tout l'enjeu.

## 🧭 Au programme

| Section | Contenu |
|---|---|
| **Laboratoire oscilloscope** | Tension, courant et déphasage en temps réel |
| **Quatre grandeurs** | P, Q, D, S : un code couleur unique, partout |
| **Une journée dans un foyer français** | Simulateur : chauffage, eau chaude et production, voiture électrique, appareils |
| **Courbe de charge** | Qui consomme quoi, heure par heure |
| **Ce que le Linky mesure vraiment** | Mémo sur la facturation et l'abonnement en kVA |

## 🚀 Utilisation

**En ligne** : ouvrez la [démo](https://lunik.github.io/Watts-voltamp-res/).

**En local** : c'est un fichier unique, sans build ni dépendance à installer.

```bash
git clone https://github.com/Lunik/Watts-voltamp-res.git
open Watts-voltamp-res/index.html   # ou double-clic
```

> Les polices (Archivo, IBM Plex) sont chargées depuis Google Fonts ; hors ligne, la page reste fonctionnelle avec les polices système.

## 🎓 Usage pédagogique

Conçu pour être **projeté en cours, partagé aux élèves ou réutilisé** dans vos propres supports (physique, électrotechnique, STI2D, BTS, formation continue, vulgarisation). Libre à vous de l'adapter, de le traduire, de le forker.

## 📄 Licence

[**CC BY 4.0**](LICENSE) : réutilisation libre, y compris commerciale et éducative, à condition de citer l'auteur (**Lunik**) et le lien vers ce dépôt.

## 🙌 Contribuer

Une erreur, une approximation physique, une idée de visualisation ? Ouvrez une [issue](https://github.com/Lunik/Watts-voltamp-res/issues) ou une pull request.
