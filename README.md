# Alternance RH — Matching CV par IA et candidature à valider

Un projet d’automatisation Make visant à faciliter la recherche
d’alternance RH, grâce à l’analyse de la correspondance entre
un CV et une offre.

## Objectif

Aider le candidat à identifier les opportunités pertinentes
et à préparer une candidature soumise à validation humaine.

## Périmètre annoncé

- Analyse de la correspondance entre le CV et l’offre avec l’IA.
- Préparation d’une candidature à examiner.
- Validation humaine avant toute utilisation de la candidature.

Les sources d’offres, le modèle d’IA, le format des résultats
et l’existence d’une étape d’envoi restent à confirmer
dans le blueprint.

## Technologies

- Make : orchestration de l’automatisation.
- IA : assistance au matching CV/offre.
- Autres applications : à préciser après vérification du scénario.

## Installation

1. Télécharger le fichier `.blueprint.json` présent dans ce dossier.
2. Créer un nouveau scénario dans Make.
3. Ouvrir le menu `…`, puis sélectionner `Import blueprint`.
4. Importer le fichier JSON.
5. Configurer les connexions demandées par les modules.
6. Adapter le CV, les critères de recherche et les paramètres de l’IA.
7. Tester avec une offre et un CV de démonstration.
8. Vérifier le résultat et le mécanisme de validation humaine.
9. Configurer la planification adaptée.


# Intégration Tally — Google Docs

Un scénario Make reliant Tally et Google Docs pour automatiser
le passage d’informations d’un formulaire vers un document.

## Objectif

Réduire les ressaisies et faciliter la préparation de documents
à partir des informations recueillies avec Tally.

## Périmètre annoncé

- Intégration entre Tally et Google Docs.
- Utilisation de Make pour coordonner les échanges.

Le déclencheur, les champs transmis et l’action Google Docs
(création, modification ou utilisation d’un modèle) restent
à confirmer dans le blueprint.

## Technologies

- Tally : formulaire.
- Make : orchestration.
- Google Docs : document.

Prérequis

- Un compte Make.
- Un formulaire Tally adapté au besoin.
- Un compte Google disposant des accès nécessaires.
- Un document ou modèle si le scénario en utilise un.
Installation

1. Télécharger le fichier `.blueprint.json` présent dans ce dossier.
2. Créer un nouveau scénario dans Make.
3. Sélectionner `…` → `Import blueprint`.
4. Importer le fichier.
5. Reconfigurer les connexions Tally et Google nécessaires.
6. Sélectionner le formulaire et les documents concernés.
7. Vérifier la correspondance entre les champs du formulaire
   et ceux utilisés dans Google Docs.
8. Effectuer un test avec une réponse fictive.
9. Contrôler le document obtenu avant d’activer le scénario.

# Agent IA — Leads email et disponibilités

Un projet Make consacré à l’assistance par IA dans le traitement
de leads, d’emails et d’informations de disponibilité.

## Objectif

Faciliter le traitement des informations liées aux contacts
et aux disponibilités, avec une automatisation adaptée
au processus de l’utilisateur.

## Périmètre à vérifier

Le nom du scénario indique trois composantes :

- Un agent IA.
- Des leads et des emails.
- Des informations de disponibilité.

Le blueprint doit être vérifié pour préciser les sources,
les actions de l’agent, les sorties produites et les éventuelles
actions sur la messagerie ou le calendrier.

## Technologies

- Make : orchestration.
- Agent IA : traitement des informations.
- Messagerie, calendrier et stockage : applications à confirmer.

## Installation

1. Télécharger le fichier `.blueprint.json` présent dans ce dossier.
2. Créer un nouveau scénario dans Make.
3. Sélectionner `…` → `Import blueprint.json`.
4. Importer le fichier.
5. Configurer les connexions demandées.
6. Sélectionner ou recréer l’agent IA si nécessaire.
7. Adapter ses instructions au besoin.
8. Vérifier les sources de contacts et de disponibilités.
9. Tester avec des données fictives.
10. Contrôler toutes les actions avant d’activer le scénario.

## Vérifications recommandées

- Vérifier la bonne identification des contacts.
- Contrôler les dates, horaires et fuseaux horaires.
- Relire les contenus produits par l’IA.
- Si le scénario envoie des emails ou crée des événements,
  vérifier les destinataires et les paramètres avant activation.




