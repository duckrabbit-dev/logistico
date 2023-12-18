# Process LOGISTICO

[drawing-logistico-process.excalidraw](./drawing-logistico-process.excalidraw)
<img src="./drawing-logistico-process.svg">

A tout moment, si quelquechose sort du protocole, il faut ouvrir un tiquet pour demander quoi faire ?

## OPERATION: Ajout d'emplacements
* Ouvrir le module "Inventaire"
* Cliquer sur "Configuration" puis "Emplacements"
* Cliquer sur "NOUVEAU"
* Selectionner l'emplacement parent: "PROGE/Stock/Picking"
* Renseigner "Nom de l'emplacement" et "Code-barres" avec le scan du code barre de l'emplacement
* Enregistrer l'emplacement
* si on veut ajouter un autre emplacement, cliquer sur "Action", puis "Dupliquer" et continuer
* Renseigner "Nom de l'emplacement" et "Code-barres" avec le scan du code barre de l'emplacement
* Enregistrer l'emplacement

## Problème: Demande d'Ajout D'emplacement Interne
* Ouvrir le module "Projet"
* Ouvrir le projet "Logistics"
* Ouvrir le template "Ajouter Emplacement(s)..."
* "Action" > "Dupliquer"
* Dans la partie "Description":
  - ajouter la zone parente des nouveaux emplacements ( Réserve ou Picking )
  - ajouter les codes barres des emplacements à créer ( 1 par ligne, avec le scanner )
* Cliquer sur le statut "NOUVEAU"
* Enregistrer

## Problème: Code Barre de produit Introuvable !
* Ouvrir le module "Projet"
* Ouvrir le projet "Logistics"
* Ouvrir le template "Code barre [CODE_BARRE] introuvable"
* "Action" > "Dupliquer"
* Remplacer dans le titre "CODE_BARRE" par le code barre introuvable
* Attacher une photo de la boite du produit introuvable (cliquer sur l'icone du trombonne)
* Cliquer sur le statut "NOUVEAU"
* Enregistrer

## OPERATION: Reception Livraison Fournisseur
* Ouvrir le module "Code-Barres"
* Cliquer sur "OPERATIONS"
* Cliquer sur "Réceptions Fournisseurs"
* Identifier la reception livraison sur le nom et adresse de l'expediteur si possible
* Selectionner la réception
* Inspection grossiere exterieur du colis
* Ouvrir le colis
* Scanner les produits et les mettre un à un dans le chariot réception
* Valider la reception, creation d'un reliquat si produit manquant

Si probleme à une étape, enregistrer une log note en tagant @support-logistic

Pousser le Chariot Réception jusqu'à la Réserve.

## OPERATION: Mise En Réserve
* Ouvrir le module "Code-Barres"
* Cliquer sur "OPERATIONS"
* Cliquer sur "Mise En Réserve"
* Ouvrir l'opération
* Scanner les produits par groupe, puis scanner l'emplacement de destination
* Répeter pour tout les groupe de produits
* Valider la mise en réserve.

## OPERATION: Transfert Interne
* Ouvrir le module "Code-Barres"
* Cliquer sur "OPERATIONS"
* Cliquer sur "Transfert internes"
* Cliquer sur NOUVEAU
* Scanner l'emplacement d'origine
* Scanner le produit transférer
* Ajouter les quantités si besoin
* Scanner l'emplacement de destination
* Recommencer l'opération pour chaque groupe de produit si besoin
* Valider le transfert


## Preparation commande client (draft)
* Ouvrir l'ecran des "codebarre/operation/livraisons"
* Selectionner une livraison

## Retour Client (draft)

