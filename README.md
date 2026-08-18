# Spec Studio

Atelier produit contract-first : des conversations vers décisions, specs et passations traçables (couche 1).

Pour les équipes produit, qui rencontre des décisions dispersées dans les conversations et perdues à la passation, ce projet permet de transformer les conversations en décisions, spécifications et passations traçables, en produisant des paquets de spécification versionnés dont chaque acceptation est enregistrée, sans dépendre de : aucune vérité produit hors du dépôt.

## État du projet

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis project.v1.yaml — ne pas éditer à la main. -->

- Situation actuelle : Dormant by owner decision 2026-08-18: no named user (internal or external), zero dogfooding (this repository's own spec is a hand-written Markdown, not a SpecPackage), and the product's real differentiator (the planning-only Biscuit handoff) has no consumer until Missions can execute. Wakes on either named condition: (a) an external pilot product team identified, or (b) Missions/Polaris mature enough to consume CreatePlanningHandoff.
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
