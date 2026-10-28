# BeeBranch — releases publiques

Dépôt **public** qui distribue uniquement les artefacts signés de BeeBranch
(le code source vit dans un dépôt privé).

- `latest.json` : manifeste signé de la version courante, lu par l'application
  via `https://github.com/Methamorphe/beebranch-releases/releases/latest/download/latest.json`.
- `rollback.json` : manifeste de la version précédente, même contrôle de
  signature.
- Chaque release contient les bundles macOS / Windows / Linux et leurs `.sig`
  minisign.

Contenu généré par la CI ; ne rien pousser à la main. La clé publique de
vérification est embarquée dans l'application.
