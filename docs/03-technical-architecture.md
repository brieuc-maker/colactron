# 03 - Architecture Technique

## Stack recommandée

### Frontend

- Next.js 15.
- React 19.
- TypeScript.
- TailwindCSS.
- shadcn/ui.
- Framer Motion.
- React Hook Form.
- Zod.
- Recharts.
- FullCalendar.

### Backend

- Supabase.
- PostgreSQL.
- Supabase Auth.
- Supabase Storage.
- Supabase Edge Functions.
- Row Level Security.

### IA

- OpenAI pour analyse, scoring, OCR intelligent, résumé et assistant documentaire.
- Embeddings pour recherche vectorielle dans les documents.

## Structure de projet recommandée

```txt
apps/
  web/
    app/
    components/
    features/
    lib/
    hooks/
    services/
    types/
    schemas/
packages/
  ui/
  config/
  database/
supabase/
  migrations/
  functions/
  seed/
docs/
```

## Principes

- Code fortement typé.
- Composants réutilisables.
- Modules métier isolés par feature.
- Validation Zod côté client et serveur.
- Sécurité par défaut via RLS.
- Toutes les actions sensibles loggées.

## Modules applicatifs

- `features/properties`.
- `features/pipeline`.
- `features/visits`.
- `features/works`.
- `features/finance`.
- `features/documents`.
- `features/map`.
- `features/ai`.
- `features/settings`.

## Déploiement

- Vercel pour le frontend.
- Supabase pour base de données, auth et storage.
- Environnements : local, staging, production.
