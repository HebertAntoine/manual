# 📚 Collection de Manuels d’Atelier & Documentation Technique

Ce dépôt regroupe une collection de **manuels d’atelier**, **notices de réparation**, **schémas techniques** et **documents d’entretien** pour divers véhicules.  
Les fichiers PDF volumineux sont stockés via **Git LFS** afin d’assurer un téléchargement fiable.

L’objectif est de fournir une base documentaire centralisée pour la restauration, la maintenance ou l’étude technique de plusieurs modèles automobiles.

---

## 🚗 Manuels disponibles

### **Peugeot 504 Cabriolet (1974)**
📁 *Dossier :* `Peugeot_504_Cabriolet_1974`

Contenu :
- `Peugeot-1205.pdf` — Manuel technique / atelier  
- `Peugeot-1212E.7z` — Archive contenant documentation supplémentaire  
- `Peugeot-1212E.pdf` — Notice atelier / schémas  
- `Peugeot-1293-R.pdf` — Documents techniques et d’entretien  

Inclut : mécanique, électricité, réglages moteur, carrosserie, spécifications techniques.

---

### **Quad Barossa 250 Sheeta**
📁 *Dossier :* `Quad_Barossa_250_Sheeta`

Contenu :
- `manuatmsc250.pdf` — Manuel complet d’atelier (moteur, châssis, transmission, électrique)

Idéal pour : entretien, réparation et diagnostic complet du quad Barossa 250.

---

### **Range Rover Classic (1990)**
📁 *Dossier :* `Range Rover Classic 1990`

Contenu :
- `manual atelier – discovery I (89)...pdf` — Manuel d’atelier Land Rover compatible Range Rover Classic 1989–1993  
- Documentation mécanique, électrique, procédures de réparation, diagnostics et tableaux de pannes.

Pour propriétaires et restaurateurs de Range Rover Classic V8.

---

## 📝 Autres fichiers

- `.gitattributes` — Configuration Git LFS  
- `.DS_Store` — Fichier système macOS (sans importance)  
- `README.md` — Ce fichier  

---

## 📦 Téléchargement et utilisation

Tous les documents sont fournis au format **PDF** ou **archive (.7z)**.

Pour télécharger :
1. Ouvrir le dossier ou fichier.
2. Cliquer sur **Download** ou **View raw**.
3. Les gros fichiers seront automatiquement gérés via **Git LFS**.

---

## 🤝 Contribution

Pour ajouter de nouveaux manuels, utiliser Git LFS pour les fichiers de plus de **100 MB** :

```bash
git lfs track "*.pdf"
git add .gitattributes
git add ton_fichier.pdf
git commit -m "Ajout d'un manuel via Git LFS"
git push