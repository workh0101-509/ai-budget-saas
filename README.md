# AI Budget SaaS

## Présentation du produit

**AI Budget** est une application web qui aide les particuliers et les freelances à comprendre où va leur argent. Elle importe leurs dépenses, les classe automatiquement grâce à l'IA et leur montre clairement s'ils respectent leur budget du mois.

## Fonctionnalités du MVP

- Création de compte et connexion sécurisée
- Ajout manuel de revenus et de dépenses
- Catégorisation automatique des dépenses par IA
- Définition d'un budget mensuel par catégorie
- Tableau de bord simple : dépenses du mois et reste disponible par catégorie

## Améliorations futures

- Connexion automatique aux comptes bancaires pour importer les transactions
- Prévisions et conseils d'épargne personnalisés générés par l'IA
- Alertes par e-mail ou notification en cas de dépassement de budget
- Application mobile et partage de budget en couple ou en équipe

## Structure du projet

- `app/` : code de l'application FastAPI (point d'entrée : `app/main.py`)
  - `api/` : routes et endpoints
  - `core/` : configuration et sécurité
  - `models/` : modèles de base de données
  - `schemas/` : schémas Pydantic (validation des données)
  - `services/` : logique métier
- `tests/` : tests automatisés (pytest)
- `infra/` : fichiers de déploiement (Docker, docker-compose)
