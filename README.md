# ai-budget-saas
## Structure du projet

- `app/` : code de l'application FastAPI (point d'entrée : `app/main.py`)
  - `api/` : routes et endpoints
  - `core/` : configuration et sécurité
  - `models/` : modèles de base de données
  - `schemas/` : schémas Pydantic (validation des données)
  - `services/` : logique métier
- `tests/` : tests automatisés (pytest)
- `infra/` : fichiers de déploiement (Docker, docker-compose)
