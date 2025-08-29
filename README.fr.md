# Projet d'Analyse et de Reporting pour Centre d'Appels Externalisé
## Description du projet

Dans le cadre de ce projet, j’ai élaboré un tableau de bord interactif sous Power BI visant à analyser les données réelles anonymisées issues d’un centre d’appels externalisé. L’entreprise facture ses clients en fonction des minutes d’appel utilisées couvrant trois principaux services : l’assistance technique, la facturation et les ventes. Elle porte une attention particulière au respect du niveau de service (SLA) à savoir le délai d'attente maiximal attendu (Within SLA). 

L’objectif principal était d’offrir au directeur régional une vision claire et synthétique des performances opérationnelles et financières du centre d’appels permettant de suivre et piloter efficacement les performances opérationnelles (ici, l'efficacité avec laquelle le centre d’appels gère ses activités quotidiennes) et financières du centre d’appels. Le tableau de bord a été conçu pour permettre un suivi précis des indicateurs clés (KPIs) à plusieurs niveaux : global, par site géographique où les équipe du service client sont localisées, et par manager et personnel.
## Stack technique

   * Power BI Desktop : Principal outil utilisé pour la conception du tableau de bord, la modélisation des données, la création de mesures DAX et la visualisation interactive.

   * DAX (Data Analysis Expressions) : Utilisation avancée pour la gestion des dates.

   * Data Modeling : Structuration efficace du modèle de données en étoile avec relations entre tables d’appels, revenus, équipes et gestionnaires.

   * Filtres et slicers interactifs : Permettent la navigation fluide par date, type d’appel, site, manager ou employé.

   * Visualisations adaptées : Graphiques en colonnes, graphiques en line, KPI cards, cartes et matrices pour clairement représenter les tendances et comparaisons.

## Axes étudiés 
### Vision globale du service clients

   * Analyse du nombre total d’appels globalement et réparti par site géographique, avec segmentation par type d’appel (technique, facturation, ventes).
  
   * Taux d'appels Within SLA calculé et présenté par sites, types d'appel et manager, garantissant un suivi de la qualité de service.

   * Durée moyenne des appels affichée, ainsi que nombre d'appels, avec détail sur les variations entre manager pour identifier les axes d’amélioration.

   * Mise en place de KPIs synthétiques sur les volumes et la qualité qui permettent de comprendre rapidement la performance du centre.

### Vision des revenus par appels

   * Suivi clair de l’évolution annuelle des revenus par site et par type d'appel, grâce à une décomposition temporelle précise (année, trimestre, mois).

   * Analyse détaillée des revenus par site et par type d’appel, contribuant à une meilleure compréhension des sources de revenu majeures.

   * Indicateurs de croissance des revenus présentés avec des comparaisons historiques permettant d’anticiper les tendances.

### Vision des performances des managers et de leurs personnels

   * Évaluation des performances individuelles des managers et équipiers à travers le volume d’appels traités et les revenus générés.

   * Analyse du temps d’attente Within SLA par équipe, fournissant des indicateurs clés pour la gestion opérationnelle et l’optimisation.

   * Identification des managers les plus performants et des équipes nécessitant un support, grâce à une visualisation claire et segmentée.

## Valeur ajoutée 

Ce tableau de bord a permis de centraliser les indicateurs essentiels pour une prise de décision rapide et éclairée par la direction régionale. La hiérarchisation des données assure la focalisation sur l’essentiel, tout en offrant la possibilité d’explorer les détails au niveau opérationnel.
