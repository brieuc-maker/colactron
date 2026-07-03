# 01 - Cahier des Charges Fonctionnel

## 1. Dashboard

Le dashboard est le cockpit principal.

### KPIs

- Nombre de biens.
- Capital investi.
- Valeur estimée du portefeuille.
- Plus-value latente.
- Cash disponible.
- Cash-flow mensuel.
- ROI moyen.
- TRI moyen.
- Chantiers en cours.
- Visites planifiées.
- Offres en attente.

### Graphiques

- Evolution du patrimoine.
- Evolution du cash-flow.
- Pipeline des biens.
- Répartition par statut.
- Répartition géographique.

## 2. Recherche immobilière

Le module recherche agrège les opportunités immobilières.

### Données d'une annonce

- Titre.
- Adresse.
- Ville.
- Prix demandé.
- Surface habitable.
- Terrain.
- PEB.
- Photos.
- Agent immobilier.
- Lien source.
- Description.

### Actions

- Ajouter au pipeline.
- Ignorer.
- Lancer une analyse IA.
- Planifier une visite.
- Exporter une fiche PDF.

## 3. Analyse de rentabilité

Chaque bien doit recevoir une analyse financière.

### Champs financiers

- Prix demandé.
- Prix cible.
- Prix d'achat négocié.
- Frais d'acquisition.
- Frais bancaires.
- Coût travaux estimé.
- Mobilier.
- Divers.
- Investissement total.
- Valeur de revente estimée.
- Loyer estimé.
- Charges.
- Cash-flow.
- ROI.
- TRI.
- Marge brute.
- Marge nette.

### Décision

- Acheter.
- Négocier.
- Planifier visite.
- Abandonner.

## 4. Pipeline

Pipeline Kanban : Recherche, Analyse, Visite planifiée, Visité, Offre envoyée, Négociation, Compromis, Acte, Travaux, Location, Vente, Archivé.

Chaque carte affiche photo, adresse, prix, ROI, TRI, score IA, responsable et prochaine action.

## 5. Fiche Bien

Onglets obligatoires : Général, Analyse, Finances, Travaux, Documents, Visites, Location, Vente, Historique.

## 6. Documents

Chaque bien doit stocker : documents d'acquisition, compromis, acte, PEB, plans, permis, devis, factures, photos, baux, contrats, expertises, assurances.

## 7. Visites

Chaque visite doit contenir : date, participants, adresse, checklist, compte rendu, photos, défauts, points positifs, estimation travaux, décision.

## 8. Travaux

Suivi des postes travaux : budget prévu, budget réel, entreprise, statut, date début, date fin, factures, photos avant/pendant/après, avancement.

## 9. Location

Gestion des locataires, baux, loyers, charges, garanties, indexations, paiements et rendement réel.

## 10. Vente

Prix cible, prix affiché, offres reçues, compromis, acte, commission agence, marge finale, documents notaire.

## 11. Historique

Toutes les actions importantes doivent être tracées : création, modification, changement de statut, upload document, décision, commentaire, suppression logique.

## 12. Permissions

Seuls les associés accèdent à l'application. Les données financières et documents sensibles doivent être protégés par des règles d'accès strictes.
