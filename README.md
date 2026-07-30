# Spec Studio

Atelier produit contract-first : des conversations vers décisions, specs et passations traçables (couche 1).

Pour les équipes produit, qui rencontre des décisions dispersées dans les conversations et perdues à la passation, ce projet permet de transformer les conversations en décisions, spécifications et passations traçables, en produisant des paquets de spécification versionnés dont chaque acceptation est enregistrée, sans dépendre de : aucune vérité produit hors du dépôt.

## État du projet

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis project.v1.yaml — ne pas éditer à la main. -->

- Situation actuelle : L'application Spec Studio (couche de commande fail-closed, persistance sur la brique data) est greffée et verte ; la passation outillée de bout en bout reste à construire.
- Maturité : usable
- Exposition : spec-published
- Confiance : medium
- Preuves vérifiées le : 2026-07-30
- Avancement : 20 % du périmètre actuellement déclaré

<!-- libre-ai:project-status:end -->

## Vérifier

- `bun install && bun run check` — la chaîne de gates du dépôt, tests inclus.
- La fiche [`project.v1.yaml`](./project.v1.yaml) est l'autorité de l'état du projet ; la section « État du projet » ci-dessus en est générée et un gate de flotte échoue si elles divergent.
- La provenance de chaque chemin migré depuis le hub est tracée dans l'index de migration de `libre-ai/libre-ai` (`ecosystem/migration-index.v1.yaml`).
