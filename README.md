# 📚 Collection de Manuels d’Atelier & Documentation Technique

Ce dépôt regroupe une collection de **manuels d’atelier**, **notices de réparation**, **schémas techniques** et **documents d’entretien** pour divers véhicules (motos, voitures, quads).  
Les fichiers PDF volumineux sont stockés via **Git LFS** pour garantir un téléchargement fiable et rapide.

L’objectif est de fournir une base documentaire centralisée pour la restauration, l’entretien ou l’étude mécanique.

---

## 🚀 Contenu du dépôt

### 🏍️ **KTM / Husqvarna**
📁 *Dossier :* `KTM_Husqvarna`

- `250_exc_tpi_2019.pdf` — Manuel utilisateur / atelier pour KTM EXC TPI 2019  
- `250_exc_tpi_2020.pdf` — Manuel utilisateur / atelier pour KTM EXC TPI 2020  

Inclut : réglages, entretien, couple de serrage, schémas électriques, moteur 2T TPI, suspension, injection, diagnostics.

---

### 🚙 **Land Rover Discovery I**
📁 *Dossier :* `Land_Rover_Discovery_1`

- `manual atelier – discovery I (89)...pdf` — Manuel d’atelier complet pour Land Rover Discovery I (1989 → années 90)  
  Mécanique, châssis, boîtes, schémas électriques, réparations et procédures de diagnostic.

---

### 🚗 **Peugeot 504 Cabriolet**
📁 *Dossier :* `Peugeot_504_Cabriolet`

- `Peugeot-1205.pdf` — Manuel technique  
- `Peugeot-1212E.7z` — Archive contenant documentation additionnelle  
- `Peugeot-1212E.pdf` — Notice atelier  
- `Peugeot-1293-R.pdf` — Documentation mécanique / électrique  

Inclut : moteur, électricité, réglages, entretien, carrosserie, fiche technique complète.

---

### 🛻 **Quad Barossa 250 Sheeta**
📁 *Dossier :* `Quad_Barossa_250_Sheeta`

- `manuatsmc250.pdf` — Manuel complet d’atelier du Barossa 250 Sheeta  
  Moteur, transmission, carburateur, schémas électriques, réglages et diagnostics.

---

### 🚘 **Range Rover Classic**
📁 *Dossier :* `Range_Rover_Classic`

- `2-range-manuel-d-atelier-de-19...pdf` — Manuel d’atelier Range Rover Classic (1986–1993)  
  Très complet : moteur, boîte, électricité, suspension, couple de serrage, procédures Land Rover officielles.

---

## 📦 Téléchargement

Tous les fichiers sont disponibles :
- en **PDF**,  
- ou en **archive (.7z)** selon les modèles,  
- avec gestion automatique via **Git LFS** pour les fichiers > 100 Mo.

---

## 🤝 Contribution

Pour ajouter d’autres manuels via Git LFS :

```bash
git lfs track "*.pdf"
git add .gitattributes
git add fichier.pdf
git commit -m "Ajout d'un nouveau manuel via Git LFS"
git push