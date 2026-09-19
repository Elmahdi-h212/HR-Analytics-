# HR Analytics Dashboard

Projet Power BI d'analyse des ressources humaines.

## Objectif

Analyser les effectifs, les salaires, les congés, les absences et la répartition des employés afin de fournir une vue synthétique de la situation RH.

## Données

- Nombre d'employés : **251**
- Employés actifs : **174**
- Employés terminés : **77**
- Âge moyen : **41.9 ans**
- Salaire moyen : **54,346**
- Score moyen des employés : **3.50 / 5**
- Colonnes : **14**

Le fichier source est disponible dans `Data/HR_Dashboard_Project.xlsx`.

## Outils

- Microsoft Power BI
- Power Query
- DAX
- Excel

## Préparation des données

La préparation a été réalisée dans Power Query : contrôle des types de données, contrôle des valeurs manquantes, contrôle des doublons et vérification de la cohérence des champs.

`TerminationDate` peut être vide pour les employés actuellement actifs ; cela correspond à la logique du dataset.

## KPI

- Total Employees
- Active Employees
- Terminated Employees
- Average Age
- Average Salary
- Average Employee Score
- Total Sick Leave
- Total Vacation Leave

## Visualisations

Le dashboard contient notamment :

- Effectifs par département
- Effectifs par sexe
- Effectifs par tranche d'âge
- Effectifs par type de contrat
- Effectifs par statut
- Salaire moyen par département
- Salaire moyen par sexe
- Congés maladie par département
- Congés annuels par département
- Filtres par année d'embauche, département et type de contrat

## Quelques constats

- Le département **Production** compte 59 employés, le plus grand effectif du dataset.
- Le département **Executive Office** présente le salaire moyen le plus élevé, à environ 83,082.
- Production totalise 447 jours de congé maladie, le total le plus élevé.
- Production totalise également 979 jours de congé annuel.
- La tranche d'âge **30-49** représente 115 employés.
- Les contrats permanents représentent 130 employés contre 121 sous contrat.

## Aperçu

Voir `Screenshots/HR_Analytics_Dashboard.jpg`.

## Structure

```text
HR-Analytics-Dashboard/
├── Data/
│   └── HR_Dashboard_Project.xlsx
├── DAX/
│   └── Measures.md
├── Documentation/
│   ├── Data_Cleaning.md
│   └── Insights.md
├── PowerBI/
│   └── README.md
├── Screenshots/
│   └── HR_Analytics_Dashboard.jpg
└── README.md
```
