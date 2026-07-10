# CamerInd

**CamerInd** est une plateforme emploi, annuaire entreprises et recrutement centrée sur le Cameroun.

Sa promesse est simple : **Trouver le job qui te ressemble, au Cameroun**.

CamerInd transforme les offres d'emploi dispersées sur WhatsApp, Telegram, les sites publics et les flux textuels en opportunités structurées, recherchables et comparables aux profils candidats.

## Pourquoi CamerInd existe

Au Cameroun, beaucoup d'opportunités circulent dans des canaux informels : groupes WhatsApp, statuts, transferts, messages Telegram, pages d'entreprises ou annonces peu structurées. Les candidats perdent du temps à chercher, vérifier, trier et comprendre si une offre correspond vraiment à leur profil.

CamerInd apporte une couche de clarté : acquisition des offres, structuration, recherche, matching CV/offres, suivi de candidature, assistance IA et outils recruteurs.

## Pour les candidats

CamerInd aide les candidats à :

- explorer des offres organisées par ville, secteur, type de contrat et mots-clés ;
- importer un CV et en extraire les compétences clés ;
- recevoir des recommandations basées sur le matching CV/offre ;
- sauvegarder les offres importantes ;
- suivre leurs candidatures ;
- échanger avec les recruteurs dans le contexte d'une offre ;
- utiliser un Coach IA pour comprendre le produit, le marché et mieux préparer leurs candidatures ;
- accéder aux plans Premium pour les scans avancés, alertes WhatsApp, score détaillé et Job Reporter personnel.

## Pour les entreprises

CamerInd fournit un workspace recruteur pour :

- créer et gérer les offres ;
- recevoir et organiser les candidatures ;
- visualiser les profils candidats en fonction de leurs offre et leurs CV ;
- suivre les messages avec les candidats ;
- améliorer la qualité de la vitrine entreprise ;
- utiliser des compositions GenUI pour comparer, auditer, relancer et prioriser les candidatures.

## Intelligence marché

CamerInd ne se limite pas à afficher des annonces. La plateforme construit progressivement une base de signaux sur le marché de l'emploi local : secteurs actifs, compétences demandées, villes dynamiques, types d'offres, tendances visibles dans les données indexées.

Le Job Reporter transforme ces signaux en rapports lisibles pour aider les candidats et les recruteurs à mieux comprendre le marché.

## Principes produit

CamerInd suit quelques règles fortes :

- pas de faux candidats, faux compteurs ou fausses offres d'emploi ;
- les fonctions essentielles seront toujours accessibles : chercher, lire une offre, postuler, sauvegarder quelques offres et discuter avec une entreprise;
- les données personnelles et les CV restent protégés ;
- l'IA aide à analyser, classer et expliquer, mais les décisions restent humaines.

## Surfaces

- **Candidat** : recherche d'offres, CV IA, matching, candidatures, favoris, alertes, Coach IA, Premium.
- **Workspace entreprise** : offres, candidatures, messages, statistiques, profil entreprise, Hub IA GenUI.

## Stack

Le projet combine :

- une application Flutter multi-surface ;
- Supabase pour Auth, Postgres, RLS, Edge Functions et Realtime ;
- un worker Node.js/TypeScript pour ingestion, parsing, matching, embeddings, notifications et reporting ;
- n8n pour les automatisations
- des intégrations WhatsApp, Telegram, e-mail et paiement Mobile Money.

Ce dépôt public présente le produit et sa vision.

## Liens

- Site candidat : https://www.camerind.com
- Workspace entreprise : https://workspace.camerind.com
- Contact : invitation@camerind.com
