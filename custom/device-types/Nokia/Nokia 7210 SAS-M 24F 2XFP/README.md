# Nokia 7210 SAS-M 24F 2XFP

## Présentation

Ce répertoire contient l'ensemble des éléments nécessaires à la création et à la maintenance du Device Type **Nokia 7210 SAS-M 24F 2XFP** pour NetBox.

Le fichier YAML est la référence utilisée pour l'importation dans NetBox.

---

# Informations générales

| Champ | Valeur |
|-------|--------|
| Constructeur | Nokia |
| Modèle | 7210 SAS-M 24F 2XFP |
| Référence constructeur | 3HE05828AAAB01 |
| Hauteur | 2U |
| Plateforme | Nokia SR OS |
| Airflow | Side-to-Rear |
| Pleine profondeur | Non |

---

# Contenu du répertoire

```
Nokia7210-SAS-M-24F-2XFP/

├── Nokia7210-SAS-M-24F-2XFP.yaml
├── README.md
├── datasheets/
├── images/
├── modules/
├── cli/
└── ios/
```

---

# Description des répertoires

## Nokia7210-SAS-M-24F-2XFP.yaml

Définition officielle du Device Type NetBox.

Ce fichier constitue la source de référence du projet.

---

## datasheets/

Documentation constructeur.

Exemples :

- Hardware Installation Guide
- Hardware Description
- Release Notes

---

## images/

Photographies du matériel.

Images recommandées :

- front.jpg
- rear.jpg
- ports.jpg
- psu.jpg
- fan.jpg
- chassis.jpg

---

## modules/

Documentation des modules compatibles.

Exemple :

- Alimentations
- Ventilateurs
- Modules optiques
- Cartes optionnelles

---

## cli/

Sorties de commandes utilisées pour vérifier le matériel.

Exemples :

- show version
- show chassis
- show card
- show port
- show inventory

---

## ios/

Versions logicielles supportées.

Exemple :

| Version | Statut |
|----------|--------|
| 24.7.R1 | Production |
| 25.3.R1 | Validation |

---

# Éléments modélisés dans NetBox

Le Device Type comprend :

- Informations générales
- Ports console
- Ports d'alimentation
- Interfaces
- Baies de modules
- Modules
- Images de façade
- Images arrière

---

# Validation

Avant publication du Device Type :

- Vérification avec la documentation Nokia
- Vérification sur un équipement réel
- Vérification de l'import NetBox
- Vérification de la cohérence des interfaces

---

# Historique

| Version | Date | Auteur | Description |
|----------|------|--------|-------------|
| 1.0 | YYYY-MM-DD | Mickael Milleret | Création du Device Type |
