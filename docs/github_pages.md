
### 3. Déploiement du site sur GitHub Pages

Créez un fichier `docs/deployment.md` avec le contenu suivant:

```markdown
# Déploiement du site sur GitHub Pages

## Étape 1 : Configuration du dépôt

1. Ajoutez la clé publique comme "Deploy Key" dans les paramètres du dépôt.
2. Ajoutez la clé privée comme secret `GITHUB_DEPLOY_KEY` dans les paramètres du dépôt.

## Étape 2 : Configurer la source de GitHub Pages

1. Allez dans les paramètres du dépôt (Settings).
2. Accédez à la section "Pages".
3. Configurez la source de déploiement sur la branche `gh-pages`
