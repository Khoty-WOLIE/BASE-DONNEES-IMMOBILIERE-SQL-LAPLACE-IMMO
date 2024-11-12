# OPC_DATA_ANALYST_PROJET3
Créez et utilisez une base de données immobilière avec SQL
# DATAImmo - Modélisation et Analyse des Données Immobilières

## Aperçu de l'entreprise

![Aperçu du site web](images/DA_projet3.PNG)

## Contexte

Je suis Data Analyst chez **Laplace Immo**, un réseau national d’agences immobilières. Le directeur général de l'entreprise souhaite exploiter les données pour améliorer la compétitivité de l'agence sur le marché immobilier. Ce projet, appelé **DATAImmo**, vise à modéliser et à analyser les données pour prédire les prix de vente des biens immobiliers et permettre aux agences régionales de mieux conseiller leurs clients.

La **CTO** de l’entreprise, **Clara Daucourt**, est en charge du projet. Elle m’a confié la mission de modifier la base de données existante pour y intégrer de nouvelles informations et d'en analyser les données afin de créer un modèle de prévision des prix.

## Objectifs du Projet

1. **Préparation du Dictionnaire des Données** : Créer un dictionnaire des données qui répertorie et décrit les informations importantes extraites de différentes sources :
   - **Demandes de valeurs foncières (DVF)** - données issues de l’open data pour les transactions immobilières.
   - **Données de l’INSEE** - informations de recensement de la population.
   - **Data.gouv.fr** - référentiel géographique français incluant les régions, communes, unités urbaines, etc.
   
2. **Modification du Schéma Relationnel** : Adapter le schéma relationnel existant pour intégrer les nouvelles données relatives aux régions et à la population. Ce nouveau schéma doit suivre la **3NF (Troisième forme normale)** pour assurer la normalisation des données et faciliter les requêtes.

3. **Implémentation de la Base de Données** : Créer les tables dans une base de données (utilisation de **SQLite**, **MySQL**, ou **PostgreSQL** recommandée) en respectant le schéma validé par la CTO.

4. **Extraction et Analyse des Données** : Réaliser des requêtes SQL pour extraire les informations pertinentes et fournir un document PDF comprenant les résultats des requêtes ainsi que les instructions SQL utilisées, avec des alias pour améliorer la lisibilité.

## Étapes du Projet

### Étape 1 : Création du Dictionnaire des Données

- **Objectif** : Répertorier et décrire toutes les données nécessaires dans un dictionnaire en suivant un template fourni par la CTO.
- **Livrable** : Un dictionnaire des données qui décrit les champs des trois fichiers de données, leurs types, et leur utilisation.

### Étape 2 : Modification du Schéma Relationnel

- **Objectif** : Adapter le schéma relationnel pour inclure les données de population et de régions.
- **Norme** : Le schéma relationnel doit respecter la **3NF** pour une base de données normalisée.
- **Livrable** : Un schéma relationnel mis à jour, validé par la CTO, avec les entités, associations et cardinalités bien définies.

### Étape 3 : Implémentation de la Base de Données

- **Objectif** : Créer la structure de la base de données en implémentant le schéma validé.
- **Technologie** : Utilisation de **SQLite**, **MySQL**, ou **PostgreSQL**.
- **Livrable** : Base de données fonctionnelle avec les tables créées selon le schéma relationnel.

### Étape 4 : Extraction et Documentation des Requêtes SQL

- **Objectif** : Extraire les données pertinentes pour l'analyse en utilisant des requêtes SQL.
- **Livrable** : Un fichier PDF contenant :
  - Les résultats des requêtes SQL.
  - Les requêtes SQL associées avec des alias pour faciliter la lecture.

## Détails Techniques

- **Fichiers** :
  - **Dictionnaire des Données** : Contient la description de chaque champ pour les trois jeux de données (DVF, INSEE, référentiel géographique).
  - **Schéma Relationnel** : Document décrivant la structure de la base de données en 3NF.
  - **Base de Données SQL** : Implémentation des tables dans un SGBD comme SQLite.
  - **Rapport PDF des Requêtes SQL** : Résultats des requêtes SQL avec les instructions et alias.

- **Compétences Utilisées** :
  - Conception de bases de données relationnelles et normalisation (3NF).
  - Création de dictionnaires de données.
  - Implémentation de schémas relationnels dans des bases de données SQL.
  - Extraction et analyse des données par requêtes SQL.

## Résumé

Ce projet m'a permis de mettre en pratique mes compétences en **gestion de bases de données** et en **analyse de données SQL** pour un projet stratégique au sein de Laplace Immo. En structurant les données de manière efficace et en extrayant des insights clés, nous offrons un avantage concurrentiel aux agences régionales. Les résultats de ce projet permettront aux équipes d’accéder à des données précises et utiles pour conseiller au mieux leurs clients.
