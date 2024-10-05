# Projet de Transformation des Données de Santé OMOP

## Aperçu du Projet
Ce projet se concentre sur la transformation de données de santé synthétiques en un modèle de données commun OMOP (Observational Medical Outcomes Partnership). L'objectif est d'assurer l'interopérabilité des données de santé en convertissant divers ensembles de données en tables standardisées OMOP, spécifiquement les tables **Person**, **Care Site** et **Provider**. Ce travail simule un scénario du monde réel d'intégration des données de santé pour faciliter la recherche et l'analyse inter-institutionnelles.

## Objectifs
Les principaux objectifs de ce projet étaient :

### Table Person :
- Transformer les données démographiques des patients en une table **Person** conforme au modèle OMOP à l'aide de Python (Pandas).
- Standardiser les données démographiques, y compris le genre et la date de naissance, dans les formats appropriés OMOP.

### Table Care Site :
- Utiliser **SQLite** pour créer et peupler une table **Care Site** avec des données sur les hôpitaux et les pharmacies.
- Assurer la cohérence des données et gérer les doublons potentiels à l'aide de contraintes SQL.

### Table Provider :
- Exploiter **Apache Spark** pour traiter les données des professionnels de santé et les mapper au modèle OMOP.
- Joindre des données provenant de plusieurs sources (professionnels et spécialités) pour générer des entrées de fournisseurs conformes à OMOP.
- Écrire le résultat dans un fichier **Parquet** pour un stockage efficace et une analyse future.

## Instructions d'Installation

### Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **Python 3.x**
- **Pandas**
- **SQLite**
- **Apache Spark**
- **PySpark**
- **Git**

