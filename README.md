# medical_center_managment-odoo
Description Générale
Ce projet consiste en le développement d’un module personnalisé Odoo dédié à la gestion complète d’un centre médical.
Le module couvre les aspects médicaux, administratifs et analytiques, en s’appuyant sur l’architecture standard d’Odoo (ORM, vues XML, sécurité, workflows).
L’objectif est de proposer une solution centralisée, modulaire et extensible, conforme aux bonnes pratiques de développement Odoo.
Objectifs Techniques

Implémenter des modèles métiers spécifiques au domaine médical

Exploiter l’ORM Odoo pour la gestion des données

Automatiser les processus administratifs (facturation, stock)

Fournir des tableaux de bord analytiques pour l’aide à la décision

Préparer l’intégration avec des outils BI externes

⚙️ Fonctionnalités
🧑‍⚕️ Gestion Médicale

Gestion des patients (dossiers, informations personnelles)

Gestion des médecins (spécialités, disponibilités)

Gestion des salles médicales

Planification et gestion des rendez-vous

🏥 Gestion Administrative

Gestion des stocks :

Pharmacie

Équipements médicaux

Facturation et génération de documents comptables

Gestion des assurances et des prises en charge

📊 Analyse et Reporting

Tableaux de bord analytiques :

Nombre de consultations

Chiffre d’affaires

Performance par spécialité et par médecin

Indicateurs clés (KPIs) basés sur les données opérationnelles

🧰 Stack Technique

ERP : Odoo

Backend : Python (ORM Odoo)

Frontend : Vues XML (Form, Tree, Kanban, Dashboard)

Base de données : PostgreSQL

Sécurité : ACL, Record Rules

Reporting : Odoo Reporting / Dashboards

🚀 Option Avancée

Intégration avec Power BI :

Extraction des données via PostgreSQL ou API

Visualisation avancée et reporting décisionnel

📁 Structure du Module
medical_center_management/
├── models/          # Modèles métiers (patients, médecins, rendez-vous, etc.)
├── views/           # Vues XML (formulaires, listes, dashboards)
├── security/        # ACL et règles de sécurité
├── data/            # Données initiales
├── reports/         # Rapports et impressions
├── __manifest__.py  # Déclaration du module
└── README.md
