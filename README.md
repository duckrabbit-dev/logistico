# Process LOGISTICO

A tout momement, si quelquechose sort du protocole, il faut ouvrir un tiquet pour demander quoi faire ?

## Reception Livraison Fournisseur
* Ouvrir l’ecran des receptions 
> codebarre / operation / receptions
* Scanner le premier produit pour aider au filtre des receptions et/ou
* Matcher la reception livraison sur le nom et adresse de l’expediteur 
(et si jamais sur le contenu entre le manifeste papier dans le colis et le bon de reception Odoo)
* Inspection grossiere exterieur de la livraison
* Selectionner dans l'ecran la reception
* Scanner les produits
* Scanner emplacement “Chariot”
* Valider la reception, creation d’un reliquat si produit manquant (trigger ticket reliquat)

Si probleme à une étape, enregistrer une log note en tagant @support-logistic

## Transfert interne	
* Scanner WH-INTERNAL
* Scanner le produit a bougé
* Scanner le nouvel emplacement
