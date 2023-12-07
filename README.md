# Process LOGISTICO

[drawing-logistico-process.excalidraw](./drawing-logistico-process.excalidraw)
<img src="./drawing-logistico-process.svg">

A tout moment, si quelquechose sort du protocole, il faut ouvrir un tiquet pour demander quoi faire ?

## Reception Livraison Fournisseur (draft)
* Ouvrir l'ecran des receptions 
> codebarre / operation / receptions
* Matcher la reception livraison sur le nom et adresse de l'expediteur 
* Selectionner dans l'ecran la reception
* Inspection grossiere exterieur du colis
* Ouvrir le colis
* Scanner les produits
* Scanner emplacement de destination
* Valider la reception, creation d'un reliquat si produit manquant (trigger ticket reliquat)

Si probleme à une étape, enregistrer une log note en tagant @support-logistic

## Transfert interne (draft)	
* Scanner WH-INTERNAL
* Scanner le produit a bougé
* Scanner le nouvel emplacement

## Preparation commande client (draft)
* Ouvrir l'ecran des "codebarre/operation/livraisons"
* Selectionner une livraison

## Retour Client (draft)

