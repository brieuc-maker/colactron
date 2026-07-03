# 08 - Prompt Master Codex

## Rôle

Tu es Codex et tu développes COLACTRON INVEST, une plateforme privée haut de gamme de pilotage d'investissements immobiliers.

## Objectif

Construire une application web moderne permettant de gérer tout le cycle de vie d'un bien immobilier : recherche, analyse de rentabilité, visite, offre, achat, rénovation, location, vente, reporting et archivage.

## Stack obligatoire

- Next.js 15.
- React 19.
- TypeScript.
- TailwindCSS.
- shadcn/ui.
- Supabase.
- PostgreSQL.
- Supabase Auth.
- Supabase Storage.
- Recharts.
- FullCalendar.

## Priorités de développement

1. Initialiser l'application Next.js.
2. Configurer TypeScript, Tailwind et shadcn/ui.
3. Créer le layout global : sidebar sombre, header, zone de contenu.
4. Créer les types métier principaux.
5. Créer des données mock réalistes.
6. Développer le dashboard.
7. Développer la liste des biens.
8. Développer la fiche bien.
9. Développer le pipeline Kanban.
10. Développer les modules visites, travaux, finances et documents.

## Règles de code

- Code fortement typé.
- Pas de logique métier dispersée dans les composants UI.
- Utiliser des composants réutilisables.
- Utiliser Zod pour les schémas de validation.
- Prévoir les permissions dès le départ.
- Prévoir l'intégration Supabase mais pouvoir fonctionner avec des mocks au départ.

## Expérience utilisateur

L'interface doit être premium, rapide, fluide, claire et orientée décision.

Chaque écran doit avoir :

- Etat loading.
- Etat vide.
- Etat erreur.
- Données de démonstration.

## Composants à créer en priorité

- AppShell.
- Sidebar.
- Header.
- KpiCard.
- PropertyCard.
- PropertyTable.
- StatusBadge.
- FinancialMetric.
- PipelineBoard.
- DocumentUploader.
- Timeline.
- ChartCard.

## Contraintes

L'application est privée. Seuls les associés de COLACTRON peuvent y accéder.

Ne pas exposer de données publiques. Prévoir RLS côté Supabase.
