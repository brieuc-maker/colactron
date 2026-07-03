# 06 - Intégrations API

## Objectif

Connecter COLACTRON INVEST aux sources de données et outils externes nécessaires à la recherche, l'analyse, la gestion et le reporting.

## Sources immobilières

### Immoweb

Récupération des annonces, photos, prix, description, adresse, surface, PEB, agent, URL.

### Zimmo

Même logique qu'Immoweb.

### Biddit

Suivi des ventes publiques et enchères.

### Notaires / agences

Possibilité d'import manuel ou semi-automatique.

## Cartographie

### Google Maps ou Mapbox

- Géolocalisation des biens.
- Carte portefeuille.
- Calcul des distances.
- Vue quartier.

## Calendrier

### Google Calendar

- Planification des visites.
- Rappels.
- Synchronisation agenda associés.

## Documents

### Google Drive optionnel

- Backup documentaire.
- Export PDF.
- Partage contrôlé.

## Odoo

Connexion future pour récupérer :

- Factures.
- Paiements.
- Fournisseurs.
- Comptabilité.
- Rentabilité consolidée.

## Emails et notifications

- Envoi d'offres.
- Rappels.
- Alertes.
- Rapports hebdomadaires.

## Banques

Connexion future pour rapprocher automatiquement les paiements et crédits.

## Principes d'intégration

- Chaque intégration doit être isolée dans un service dédié.
- Les données externes doivent être normalisées avant stockage.
- Les erreurs API doivent être loggées.
- Les imports doivent pouvoir être rejoués.
