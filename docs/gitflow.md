
### 6. Description détaillée du flux de travail Git Flow utilisé

Créez un fichier `docs/gitflow.md` avec le contenu suivant:

```markdown
# Description détaillée du flux de travail Git Flow utilisé

## Branches principales

- `main` : Contient le code de production.
- `develop` : Contient le code pour la prochaine version.

## Branches de support

- `feature/*` : Utilisé pour développer de nouvelles fonctionnalités.
- `release/*` : Préparation des nouvelles versions.
- `hotfix/*` : Corrections rapides en production.

## Workflow Git Flow

1. **Créer une nouvelle fonctionnalité :**
   ```sh
   git checkout develop
   git checkout -b feature/ma-nouvelle-fonctionnalité
