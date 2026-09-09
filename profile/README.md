# Vadato digital

Dépôts de code de Vadato. Une application = un dépôt, créé à partir du modèle `app-template`.

## Comment on travaille

1. On part d'un `main` à jour, on crée une branche `prenom/sujet`.
2. On travaille avec son agent (Claude Code, Qwen Code), qui lit `AGENTS.md` et respecte les garde-fous.
3. `scripts/verifier.sh` doit être vert avant de pousser.
4. On ouvre une pull request. Elle est relue et mergée par l'équipe core.
5. `main` est protégée : pas de push direct, pas de push forcé, pas de suppression, pour personne.

Le handbook complet est dans le dépôt privé `engineering` (`docs/HANDBOOK.md`).
Un problème, une question : ouvrir une issue dans le dépôt concerné.
