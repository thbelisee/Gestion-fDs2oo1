# Gestion-fDs2oo1
App html avec stockage local pour gestion de stock
1. À quoi sert l’application
  Mon Maquis remplace le cahier et le bic. Elle permet de suivre le stock, les achats, les ventes et les pertes du maquis, et de savoir   combien tu gagnes. Elle fonctionne sur le téléphone, sans internet une fois installée, et garde les données sur le téléphone.
2. Les principes à connaître
•	Le stock se calcule tout seul : achats reçus − produits vendus − pertes. On ne tape jamais le stock à la main, sauf la quantité de départ quand on crée un produit.
•	Bénéfice net = ventes − coût des produits vendus − pertes.
•	Un achat n’est pas une dépense perdue : il remplit le stock. Il ne réduit le bénéfice que lorsque le produit est vendu ou perdu.
•	Chaque vente garde le prix de vente du moment, donc changer un prix plus tard ne modifie pas les anciennes ventes.
•	Le coût d’une vente utilise le prix d’achat inscrit sur la fiche du produit. Si tu mets à jour la fiche après un achat plus cher, les anciennes bouteilles encore en stock seront comptées à ce nouveau prix quand elles seront vendues.
•	Les données restent uniquement sur le téléphone. Il n’y a pas de synchronisation entre plusieurs téléphones.
3. Les cinq écrans
Stock
Touche « + Nouveau produit » et remplis :
•	le nom (libre : Brakina, Coca, Riz gras…) ;
•	le type : Bière, Boisson sucrée, Jus, Vin, Liqueur, Repas ou Autre ;
•	le conditionnement, dont la liste dépend du type (canette, petite bouteille, grande bouteille, verre, plat…) ;
•	le prix d’achat et le prix de vente, fixés par toi ;
•	l’alerte de stock bas et la quantité déjà en stock.
Touche un produit pour le modifier ou l’archiver. Une quantité en rouge a atteint le seuil d’alerte. En bas, l’application affiche la valeur du stock au prix d’achat.
Vente
1.	Cherche le produit, puis touche « + » pour chaque article vendu (« − » pour retirer).
2.	Touche « Valider ». Une fenêtre s’ouvre : choisis le moyen de paiement, entre le numéro du reçu et, pour un paiement mobile, le téléphone du client.
3.	Touche « Enregistrer la vente ». Le stock baisse automatiquement. L’application refuse de vendre plus que le stock disponible.
Pour annuler une vente : onglet Bilan, liste des ventes, touche ✕. Les articles reviennent en stock.
Achats
1.	Choisis le produit, la quantité reçue et le prix d’achat unitaire (déjà rempli avec le prix de la fiche).
2.	Choisis « Payé par » et remplis les informations demandées (voir section 4).
3.	Si le prix d’achat a changé, une fenêtre propose : Mettre à jour la fiche (tu peux aussi corriger le prix de vente), Garder les anciens prix ou Annuler l’achat.
Un achat ne peut pas être supprimé si une partie de ce stock a déjà été vendue ou perdue.
Pertes
Pour la casse, un produit périmé ou gâté, une boisson offerte ou un manque : choisis le produit, la quantité et la raison. Le stock baisse et la perte est comptée au prix d’achat. Supprimer une perte remet le stock.
Bilan
•	Choisis la période : Aujourd’hui, 7 jours, Ce mois ou Tout.
•	Lis le bénéfice net, puis le détail : ventes, coût des produits vendus, marge, pertes.
•	Compare l’argent encaissé et dépensé par moyen de paiement avec ta caisse et ton compte mobile.
•	Consulte la valeur du stock, la liste des produits en stock bas et les ventes de la période.
4. Moyens de paiement et informations demandées
Les moyens proposés sont Cash, Orange Money et Moov Money. Tous les champs sont obligatoires : l’application refuse d’enregistrer s’il en manque un. Un numéro de téléphone doit comporter au moins 8 chiffres.
Opération	Moyen de paiement	Informations demandées
Vente	Cash	Numéro du reçu
Vente	Orange Money ou Moov Money	Numéro du reçu et téléphone du client (le numéro qui a transféré)
Achat	Cash	Nom de la structure qui a reçu l’argent
Achat	Orange Money ou Moov Money	Nom de la structure, numéro qui a envoyé (le tien) et numéro qui a reçu (celui du fournisseur)

5. Rapport et sauvegarde
Le rapport à lire
Dans le Bilan, la section « Rapport à lire » crée un texte simple avec le résumé, le stock, les ventes, les achats et les pertes de la période choisie. Tu peux le télécharger (.txt) ou l’envoyer par WhatsApp.
La sauvegarde de sécurité
Le bouton « Sauvegarder (pour restaurer) » crée un fichier qui n’est pas fait pour être lu : il sert à tout remettre si tu perds tes données ou si tu changes de téléphone.
•	Fais une sauvegarde chaque semaine et envoie-la-toi sur WhatsApp ou par e-mail.
•	« Restaurer une sauvegarde » remplace toutes les données actuelles par celles du fichier.
•	« Tout effacer » supprime tout de façon définitive : n’y touche qu’après une sauvegarde.
6. Installer l’application sur un autre iPhone
Important : utilise Safari. Sur iPhone, seul Safari peut installer l’application sur l’écran d’accueil. Il faut aussi une connexion internet pour cette première installation.
1.	Ouvre Safari (pas Chrome, ni WhatsApp) et entre l’adresse de l’application obtenu après l'avoir hébergé sur Github,netlify etc... : 

2.	Vérifie que l’application s’affiche.
3.	Touche le bouton Partager (le carré avec une flèche vers le haut), fais défiler la liste et choisis Sur l’écran d’accueil.
4.	Garde le nom « Mon Maquis » (ou change-le) puis touche Ajouter.
5.	Ferme Safari et ouvre l’application avec sa nouvelle icône. Ouvre-la une première fois avec internet : elle pourra ensuite fonctionner sans connexion.
6.	Saisis tes données uniquement depuis cette icône. Les données de Safari et celles de l’icône sont séparées.
Reprendre les données de l’ancien téléphone
1.	Sur l’ancien téléphone : Bilan, puis « Sauvegarder (pour restaurer) ».
2.	Envoie le fichier obtenu au nouveau téléphone (WhatsApp, e-mail ou AirDrop) et enregistre-le dans l’application Fichiers.
3.	Sur le nouveau téléphone, ouvre l’application depuis son icône : Bilan, puis « Restaurer une sauvegarde », et choisis le fichier.
Chaque téléphone a ses propres données. Si deux téléphones servent en même temps, leurs ventes ne se mélangent pas : choisis un seul téléphone pour la caisse.
7. Bonnes pratiques
•	Ne vide pas les données de Safari (Réglages, Safari, Effacer historique et données de sites) sans sauvegarde récente.
•	Garde le même téléphone pour la caisse et ouvre toujours l’application depuis la même icône.
•	Évite les applications « nettoyeur » qui effacent les données des navigateurs.
•	Garde assez d’espace libre sur le téléphone.
•	Teste la sauvegarde dès l’installation, pour être sûr qu’elle fonctionne sur ton téléphone.
8. En cas de problème
Problème	Que faire
Un produit n’apparaît pas dans Vente	Vérifie dans Stock qu’il n’est pas archivé. S’il est grisé, son stock est à 0 : enregistre un achat.
Message « Stock insuffisant »	Il reste moins d’articles que la quantité demandée. Vérifie le stock ou enregistre l’achat manquant.
L’application s’ouvre vide	Tu l’as sans doute ouverte depuis Safari ou une autre icône. Ouvre-la depuis l’icône installée. Sinon, restaure ta dernière sauvegarde.
L’ancienne version s’affiche après une mise à jour	Connecte-toi à internet, ferme complètement l’application et rouvre-la.
Un numéro de téléphone est refusé	Il faut au moins 8 chiffres, sans lettres. Les espaces sont acceptés.
Les données ont disparu	Bilan, « Restaurer une sauvegarde », puis choisis ton dernier fichier de sauvegarde.

