# NextMove

NextMove est une application d’échecs cross-platform développée dans le but de maintenir une veille technologique active autour de l’écosystème .NET moderne.

Le projet combine une application desktop Windows en WinUI 3, une application mobile iOS en .NET MAUI, une application WEB Blazor ainsi qu’une API ASP.NET Core hébergée sur Azure.  
L’objectif n’est pas seulement fonctionnel, mais également architectural et technique : expérimenter des pratiques modernes de développement logiciel, de cloud computing et de qualité applicative dans un contexte concret.

## Objectifs du projet

- Développer une application moderne autour de l'étude du jeu d’échecs
- Mutualiser un maximum de code entre desktop, web et mobile
- Mettre en place une architecture propre, maintenable et testable
- Expérimenter les technologies récentes de l’écosystème .NET
- Implémenter une chaîne CI/CD complète avec Azure DevOps
- Approfondir les pratiques de qualité logicielle et d’observabilité

## Stack technique

### Frontend
- WinUI 3 (desktop Windows)
- .NET MAUI (iOS)
- MVVM Toolkit
- XAML
- Blazor

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- JWT Authentication

### Infrastructure & Cloud
- Azure App Service
- Azure SQL Database

### Qualité & Outillage
- xUnit
- FluentAssertions
- GitHub Copilot
- Serilog
- Azure DevOps Pipelines

## Fonctionnalités prévues

- Import/export PGN
- Gestion et suivi des connaissances (ouvertures, finales, tactiques, ...)
- Analyse de parties
- Mode hors ligne avec synchronisation
- Authentification utilisateur
- Historique et synchronisation cloud
- Statistiques et suivi de progression

## Architecture

Le projet suit une architecture modulaire inspirée de la Clean Architecture afin de séparer clairement :

- la logique métier,
- les cas d’usage,
- l’infrastructure,
- et les interfaces utilisateur.

# Pourquoi ce projet ?

Ce projet est avant tout un laboratoire technique personnel destiné à :

- rester à jour sur les technologies modernes .NET
- expérimenter des pratiques d’architecture logicielle
- approfondir les problématiques de cloud et de CI/CD
- construire une base applicative réaliste et maintenable sur le long terme

# Statut du projet

Projet en cours de conception et de développement.

