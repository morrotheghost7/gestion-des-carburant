GESTION DES CARBURANTS
======================

Application web de gestion du carburant du parc de véhicules d'une entreprise.

PROJET SCOLAIRE
---------------
Ceci est un projet scolaire. Il a été réalisé à des fins pédagogiques sous la supervision de mon professeur, Elghatas. Merci pour son accompagnement et ses conseils.

L'entreprise (Société Nationale des Infrastructures Publiques), les utilisateurs, les véhicules et toutes les données sont fictifs.

Réalisé par : oualid dahmani

FONCTIONNALITÉS
---------------
Les employés demandent du carburant pour un véhicule. Les responsables approuvent ou rejettent les demandes, enregistrent les alimentations réelles et suivent la consommation. Les administrateurs gèrent les utilisateurs, les prix et les budgets.

- Demandes de carburant avec numéro automatique (BC-2026-0001), approbation ou rejet motivé, bon de carburant imprimable
- Véhicules avec quota mensuel et barre d'utilisation
- Alimentations avec détection automatique des consommations anormales (15 % ou plus au-dessus de la normale en L/100 km)
- Tableau de bord avec indicateurs, demandes à traiter et graphiques mensuels (litres et coût)
- Rapports mensuels par véhicule et par département, export CSV
- Budget annuel par département et prix des carburants
- Notifications, rappels des demandes en retard et journal d'activité
- Sauvegarde et restauration des données au format JSON
- Trois rôles : Administrateur, Responsable, Employé, avec contrôle des droits sur chaque page
- Langues : français, arabe (de droite à gauche) et anglais
- Thèmes sombre et clair
- Bon de carburant avec QR code : l'employé le scanne et saisit son alimentation, puis le responsable la valide
- Scanner de QR code intégré (caméra ou import d'une image)
- Connexion rapide par carte QR personnelle, protégée par un code PIN à 4 chiffres (3 essais), carte révocable par l'administrateur
- Cartes imprimables et téléchargeables en image PNG (recto et verso)

Contexte marocain : montants en DH (1 250,50 DH), dates au format jj/mm/aaaa, carburants Gasoil 50, Sans plomb 95 et Gasoil Premium, stations Afriquia, Total, Shell, Petrom et Winxo, immatriculations du type 12345-A-6.

COMPTES DE DÉMONSTRATION
------------------------
- admin / admin123 (Administrateur)
- manager / manager123 (Responsable)
- employee / employee123 (Employé)

Codes PIN de démonstration pour la connexion par carte : 1111 (admin), 2222 (manager), 3333 (employee).

REMARQUES TECHNIQUES
--------------------
- HTML, CSS et JavaScript purs, sans framework ni bibliothèque. Toute l'application tient dans le fichier index.html.
- Les données sont enregistrées dans le navigateur (localStorage). Le bouton Réinitialiser les données de démonstration (administrateur) rétablit les données de départ.
- Les mots de passe et les codes PIN sont conservés en clair dans le navigateur car il s'agit d'une démonstration. Une vraie application utiliserait un serveur et des mots de passe chiffrés.

PROFESSEUR
----------
Projet encadré par Elghatas.
