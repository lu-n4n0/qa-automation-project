# Plan de Test – Projet QA Automation sur automationintesting.online

## 1. Introduction

Ce document décrit la stratégie et la portée des tests pour le site [https://automationintesting.online/](https://automationintesting.online/), un site de démonstration conçu pour la pratique des tests logiciels.

## 2. Objectifs des tests

- Garantir la qualité fonctionnelle et la stabilité des fonctionnalités principales.
- Valider les interfaces utilisateur et les interactions.
- Vérifier le bon fonctionnement de l’API REST exposée.
- Assurer une couverture suffisante des tests manuels et automatisés.
- Détecter et documenter les anomalies.
- Permettre une exécution régulière de tests de non-régression.

## 3. Périmètre des tests

Les tests porteront sur les modules suivants :

- Formulaire de réservation (booking form)
- Authentification et backoffice
- Gestion des chambres (CRUD)
- API REST (réservations, utilisateurs, chambres)
- Navigation et interface utilisateur (UI/UX)

## 4. Types de tests

| Type de test           | Description                                    |
|-----------------------|------------------------------------------------|
| Tests fonctionnels     | Tests manuels et automatisés sur les fonctionnalités principales |
| Tests d’API            | Validation des endpoints API via Postman ou scripts |
| Tests UI              | Tests automatisés des interfaces utilisateur via Selenium/Cypress |
| Tests de non-régression| Exécution régulière des tests automatisés pour détecter les régressions |
| Tests de performance   | (Optionnel) Mesure des temps de réponse |

## 5. Environnement de test

- Site web accessible à l’URL : [https://automationintesting.online/](https://automationintesting.online/)
- Navigateurs supportés : Chrome (dernière version), Firefox
- Outils : Postman, Cypress, Selenium WebDriver, PyTest, etc.
- Système d’exploitation : Windows / macOS / Linux

## 6. Critères d’entrée

- Site accessible et stable
- Accès aux outils de test et environnements configurés
- Jeux de données de test validés

## 7. Critères de sortie

- Tous les cas de test critiques exécutés avec succès
- Les anomalies majeures corrigées ou consignées
- Rapports de test validés et disponibles
- Environnements remis en état stable

## 8. Livrables

- Cas de tests manuels (fichier Markdown)
- Scripts de tests automatisés (UI et API)
- Rapports d’exécution et d’anomalies
- Documentation du projet (README, plan de test, guide d’exécution)
