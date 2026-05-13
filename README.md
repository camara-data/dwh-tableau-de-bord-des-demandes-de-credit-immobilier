# Mini Projet SSIS-Sql Server-Power BI-Analyse des demandes de prêts immobiliers
## 1) Contexte
Le réseau d’agences bancaires rencontrait plusieurs difficultés dans le traitement des demandes de prêts immobiliers:
* des délais de décision trop longs;
* des analyses réalisées principalement de manière manuelle;
* des données dispersées entre plusieurs sources;
* une qualité de dossier variable selon les agences.

Les conseillers bancaires devaient analyser plusieurs informations avant de prendre une décision:

* situation professionnelle;
* revenus;
* situation familiale;
* apport personnel;
* capacité de remboursement.
Ce processus était chronophage et rendait le suivi des demandes complexe pour les agences et la cellule centrale.

## 2) Approche technique
Mise en place une solution BI complète basée sur SQL Server, SSIS et Power BI afin de centraliser, transformer et analyser les données des demandes de prêts immobiliers.

### Approche mise en place
* Centralisation des données dans un Data Warehouse sous SQL Server;
* Mise en place d’un modèle de données en étoile avec:
  * une table de faits des demandes de prêts,
  * plusieurs tables de dimensions;
* Développement de flux ETL avec SSIS pour:
  * extraire les données depuis SQL Server et Excel,
  * nettoyer et transformer les données,
  * corriger les anomalies et incohérences,
  * charger les données dans l’entrepôt;
* Automatisation des traitements avec SQL Server Agent;
* Création de tableaux de bord Power BI pour:
  * le suivi des demandes de prêts,
  * l’analyse des profils clients,
  * le pilotage des performances des agences.

### Traitements réalisés
* nettoyage des données incohérentes;
* gestion des valeurs nulles;
* standardisation des données;
* intégration de plusieurs sources;
* consolidation et historisation des données.
## 3) Les insights générés
Les tableaux de bord ont permis de mieux comprendre et piloter l’activité des prêts immobiliers grâce à:
* l’identification des profils clients ayant le meilleur taux d’acceptation;
* l’analyse de l’impact des revenus, de l’apport personnel et de la situation familiale sur les décisions de prêts;
* le suivi des délais de traitement des demandes;
* la comparaison des performances entre agences;
* la détection des anomalies et incohérences dans les données;
* une meilleure visibilité globale sur le processus de décision.

### Valeur métier obtenue
* Réduction du temps d’analyse des dossiers;
* Amélioration de la qualité des décisions de prêts;
* Centralisation des données dans une plateforme unique;
* Aide à la prise de décision pour les conseillers bancaires et la cellule centrale;
* Amélioration du pilotage global des demandes de prêts immobiliers.
