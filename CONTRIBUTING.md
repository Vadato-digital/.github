# Contribuer aux dépôts Vadato

- Une branche par sujet, nommée `prenom/sujet`, créée depuis un `main` à jour.
- Commits en français au format `type: description` (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`).
- Aucun secret dans le code ni dans git. Les variables vont dans `.env` (ignoré) et leurs noms dans `.env.example`.
- Une pull request par sujet, avec le modèle rempli. Relecture et merge par l'équipe core.
- `main` est protégée : pas de push direct, pas de push forcé, pas de suppression.
- Les agents de code (Claude Code, Qwen Code) suivent `AGENTS.md` dans chaque dépôt.

Le détail (rôles, revue, incidents, glossaire) est dans le dépôt privé `engineering`, `docs/HANDBOOK.md`.
