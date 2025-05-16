# 🧑‍💼 Gestion des Employés - Application Web d'entreprise

Une application web complète pour la gestion des employés au sein d'une ou plusieurs entreprises, développée avec les dernières technologies Java 🌐.

## 📌 Description

Cette application permet à chaque entreprise de gérer ses propres directions, employés, et les expériences professionnelles associées à chaque salarié.

Chaque entreprise possède un **profil sécurisé** et n'a accès **qu'à ses propres données**. Elle peut :

- Créer et gérer les informations de son entreprise 🏢 
- Ajouter, modifier ou supprimer ses directions 📂 
- Gérer les employés d’une direction 👥
- Visualiser une fiche détaillée par employé 📄
- Suivre les expériences professionnelles des salariés 🧳

## 🛠️ Technologies utilisées

| Catégorie              | Technologie              |
|------------------------|--------------------------|
| Langage                | `Java 17` ☕             |
| Backend                | `Spring Boot 3` 🚀       |
| Frontend               | `JSF` + `PrimeFaces` 🎨  |
| Base de données        | `MySQL` 🗄️              |
| Migration DB           | `Flyway` 🔄             |
| Librairies             | `Lombok`, `MapStruct` 🧰 |
| Sécurité               | `Spring Security` 🔐     |
| Tests unitaires        | `JUnit 5`, `Mockito` 🧪   |
| Objectif couverture    | ≥ `80%` 📊               |
| UI/Design              | `Bootstrap` 💅           |

## ✨ Fonctionnalités principales

- ✅ Créer une entreprise (nom, adresse, site web, secteur d'activité)
- ✅ Lister les directions d’une entreprise
- ✅ Ajouter une direction avec ses employés  
- ✅ Afficher les informations d’une direction (nom, directeur, employés)
- ✅ Ajouter un employé à une direction
- ✅ Modifier les informations d’un employé
- ✅ Afficher la fiche complète d’un employé :
  
  - Nom, Prénom
  - Adresse, Téléphone, Email
  - Fonction, Date d'entrée, Salaire annuel
  - Direction
  - Expériences pro : date début/fin, fonction, lieu, description

## 🔐 Sécurité

Chaque entreprise dispose de son propre compte sécurisé via **Spring Security**. Aucune entreprise ne peut accéder aux données d'une autre.

## 🧪 Tests

- Outils : `JUnit 5` & `Mockito`
- Couverture de code visée : **80% minimum**

## 🧱 Architecture du projet

- Architecture **MVC** (Model - View - Controller)
- Séparation claire des couches : `controller`, `service`, `repository`, `model`, `dto`
- Frontend basé sur **JSF** + **PrimeFaces**
- Backend REST avec **Spring Boot**

## 📁 Structure recommandée

```bash
gestion_employes/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/gestion/employes/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── repository/
│   │   │       ├── model/
│   │   │       └── security/
│   │   ├── resources/
│   │   │   └── application.yml
│   │   └── webapp/
│   │       └── WEB-INF/views/
│   │           ├── layout/
│   │           ├── entreprise/
│   │           ├── direction/
│   │           └── employe/
│   └── test/
│       └── com/gestion/employes/
├── pom.xml
└── README.md

🛣️ Objectifs
📆 Court terme
 Création des entités principales

 Mise en place de l'authentification sécurisée

 Implémentation de la base de données avec Flyway

 Intégration de PrimeFaces pour le front

🚀 Long terme
 Génération de rapports RH 📊

 Export des fiches employé en PDF/Excel 📄
 Statistiques dynamiques des employés 📈
 Gestion multilingue (fr/en) 🌍
 Interface Super-Admin globale 🧑‍💼
 Déploiement sur un serveur distant ☁️

📷 Aperçu (à venir)
Ajoutez ici des captures d’écran de l’interface une fois disponible.

📜 Licence
Ce projet est open-source et peut être utilisé à des fins éducatives ou professionnelles.

# 🧑‍💼 Gestion des Employés - Application Web d'entreprise

![Java](https://img.shields.io/badge/Java-17-blue.svg)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen)
![JSF](https://img.shields.io/badge/JSF-PrimeFaces-purple)
![Tests](https://img.shields.io/badge/Test%20Coverage-80%25-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Status](https://img.shields.io/badge/Status-En%20cours-yellow)


👨‍💻 Auteur
Annisse Artadji – Développeur Fullstack / Designer / Admin systeme (linux et windows)

