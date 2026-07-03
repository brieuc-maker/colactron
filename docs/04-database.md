# 04 - Base de Données

## Tables principales

### `profiles`

Utilisateur applicatif lié à Supabase Auth.

Champs : id, email, full_name, role, avatar_url, created_at, updated_at.

### `properties`

Bien immobilier.

Champs : id, title, address, city, postal_code, country, latitude, longitude, status, strategy, asking_price, purchase_price, estimated_resale_value, estimated_rent, peb, living_area, land_area, bedrooms, description, source_url, created_by, created_at, updated_at, deleted_at.

### `property_analysis`

Analyse financière et IA d'un bien.

Champs : property_id, market_value, acquisition_costs, renovation_budget, furniture_budget, total_investment, resale_value, monthly_rent, monthly_charges, gross_margin, net_margin, roi, irr, cashflow, ai_score, ai_recommendation, risk_level.

### `property_documents`

Documents liés aux biens.

Champs : property_id, category, file_name, file_path, mime_type, size, ocr_text, uploaded_by, created_at.

### `property_visits`

Visites planifiées ou réalisées.

Champs : property_id, visit_date, participants, status, report, positive_points, negative_points, renovation_notes, decision, created_by.

### `property_work_items`

Postes travaux.

Champs : property_id, title, contractor_id, planned_budget, actual_cost, status, start_date, end_date, progress, notes.

### `property_expenses`

Dépenses.

Champs : property_id, category, amount, vat_amount, total_amount, invoice_date, due_date, paid_at, document_id.

### `property_income`

Revenus locatifs ou vente.

Champs : property_id, type, amount, period_start, period_end, paid_at, tenant_id, notes.

### `property_sales`

Suivi de revente.

Champs : property_id, listing_price, accepted_offer, sale_price, agency_commission, notary_date, margin_final.

### `timeline_events`

Historique.

Champs : property_id, actor_id, event_type, title, description, metadata, created_at.

### `audit_logs`

Journal système.

Champs : actor_id, action, entity_type, entity_id, before, after, created_at.

## Sécurité RLS

Principe : seuls les utilisateurs authentifiés et associés peuvent accéder aux données. Les administrateurs ont accès total. Les suppressions doivent être logiques via `deleted_at` sauf exception.

## Index recommandés

- properties(status).
- properties(city).
- properties(strategy).
- property_analysis(ai_score).
- property_analysis(roi).
- property_documents(property_id, category).
- timeline_events(property_id, created_at).
