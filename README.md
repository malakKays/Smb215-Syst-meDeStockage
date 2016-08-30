[logo]: https://github.com/malakKays/Smb215-SystemeDeStockage/blob/master/attention2.png?raw=true

# ![alt text][logo] Nouveau lien vers le projet : https://github.com/StockManagement/
#
#
#

# Smb215-SystemeDeStockage
projet SMB215

# Présentation du projet
## Objectifs
Le canal de distribution est l'une des politiques du Marketing. De plus, la distribution est un moyen d'action sur le marché. Dans le cadre de la résolution des problèmes de distribution (lieu, temps, assortissent et quantité) nous souhaitons de subir ce projet de notre façon. Dans le but d'amélioration des services de distribution, nous avons planifié ce projet de sorte qu'il amène une espace économique plus rentable et plus efficace pour tous les acteurs dans un canal de distribution.

## Périmètre
Les profiteurs de ce projet, sont tous les participants aux canaux de distributions. Pour cela ils sont répartis en trois groupes :
- Les consommateurs, ce sont les utilisateurs finaux du système et ils représentent les clients des supermarchés et des autres magasins de ventes.
- Les marchands, ce sont les propriétaires et les investisseurs des magasins et des boutiques de ventes. De plus, ils représentent les détaillants et les grossistes des marchandises à vendre pour des clients finaux ou bien pour des autres vendeurs.
- Les producteurs, ce sont les producteurs des articles et les importateurs des marchandises de l'extérieures. Ils représentent le début du canal de distribution.
Notons que chaque groupe représente un rôle, par exemple un courtier pour être un marchand qui peut vendre ces marchandises d'un part, et un client qui achetés ces marchandises d'un producteur d'autre part.

## Hors Périmètre
Les agences de délivrassions seront exclus de ce projet, auquel ils n'auront aucun rôle. La délivrassions doit être effectué par les marchands ou par les producteurs.

## Exigences
Les exigences sont réparties sur les trois rôles de la manière suivante :

### Consommateur
- Identification : le client aura un compte, Il peut dans son compte préciser la location de sa maison ou de son travail et autre pour qu’il ne précise pas sa location à chaque fois qu’il envoie une requête.
- Fonctionnalités :
    - voir en ligne les produits selon les catégories, leurs prix et tout ce qu’il en a besoin
    - pouvoir demander un produit partout il était
    - pouvoir scanner les codes-barres des produits d’après son Smartphone pour avoir tous les détails nécessaires
    - pouvoir envoyer sa location sur le map
    - les produits demandés seront sauvegardés, pouvoir altérer la requête tant qu’elle n’est pas encore traitée et envoyée 
    - les produits achetés seront sauvegardés et il peut les voir
    - pouvoir voir à chaque instant sa requête est ou dur le map
    - pouvoir choisir l’employé qu’il veut le servir
    - pouvoir ajouter dans une liste les produits qu'il en a besoin qui n'existent pas chez le marchand
    - pouvoir ajouter dans une liste des produits qu’il désire acheter lorsqu’il a de l’argent ou durant un sale, etc. 
    - pouvoir préciser ses intérêts parmis les catégories des produits
    - pouvoir voir la liste des clients et follow certain clients pour voir la liste des produits qu’ils ont achetés, et il peut chercher un client précis
    - pouvoir reporter un produit
    - pouvoir laisser des commentaires sur la qualité des produits, sur la qualité du service, sur les employés, etc.
    - pouvoir voir des statistiques sur chaque type de produit:
        - la fréquence de vente d’un tel produit
        - par semaine/ par mois/ par année
    - Notification :
        - recevoir la durée approximative durant laquelle le produit arrive lorsqu'il demande un produit
        - il doit notifier que le produit est reçu
        - Il doit être notifié s’il y en a un sale ou s’il y en a de nouveaux produits spéciaux ou innovants
        - il doit recevoir des notifications s’il en a de nouveaux sur les catégories des produits qu'ils l'intéressent
         
### Marchands
- Identification:
    - Le marchand a un compte
    - pouvoir voir tous les comptes de ses clients qui sont des consommateurs
    - pouvoir être un client pour un ou plusieurs producteurs
- Fonctionnalités par rapport à ses produits et ses employés:
    - Tous ses produits sont sauvegardés dans des catégories dans la base des données avec leurs prix, les couleurs disponibles, etc.
    - Pouvoir mettre une liste des produits qu’il en a besoin
    - Pouvoir voir des statistiques sur:
        - la fréquence de vente d’un tel produit
        - par semaine/ par mois/ par année
        - la fréquence de demande d’un certain employé par les clients
    - Pouvoir voir tous les produits qui ont dépassé la date d’expiration, et les produits qui ont une date d’expiration avant une telle date
    - à chaque instant, il peut voir ou est chaque employé sur le map
- Fonctionnalités par rapport aux consommateurs:
    - Recevoir les requêtes des clients
    - Le produit vendu est enlevé de son stocke et ajouté à la liste des produits achetés par le client
    - Pouvoir avoir une liste de produits achetés par chaque client
    - Pouvoir voir les intérêts de ses clients et les produits qu'ils en a besoin et n'existent pas chez lui
- Fonctionnalités par rapport aux producteurs:
    - mettre une liste des produits qu'il en a besoin
    - mettre une liste de nouveaux produits proposés qu'ils peuvent être vendus dans le marché
- Notification consommateurs:
    - Lorsqu’il traite une requête, il doit notifier le client de la durée de son arrivée
    - Recevoir une notification des produits délivrés et les commentaires des clients s’il y en a
- Notification producteurs:
    - Recevoir une notification de nouveaux produits chez le producteur
    - notifier le produit que les produits sont reçus

### Producteur
- Identification:
    - Le producteur a un compte
    - pouvoir voir tous les comptes de ses clients qui sont des marchands
- Fonctionnalités:
    - Tous ses produits sont sauvegardés dans des catégories dans la base des données avec leurs prix, les couleurs disponibles, etc.
    - Pouvoir voir des statistiques sur:
        - La fréquence de vente d’un tel produit
        - Par semaine/ par mois/ par année
    - voir les listes des produits que les marchands en ont besoin
    - voir les listes de nouveaux produits proposés par les marchands
- Notification:
    - notifier les marchands de nouveaux produits
    - notifier les marchands de la durée qu'il en a besoin pour délivrer les produits demandés par les marchands

## Contraintes
Pour ce moment, pas de contraintes remarquables. Les contraintes rencontrées durant le travail seront mentionnées dans cette rubrique.

# Organisation du projet

## Organisation de l'équipe
L'équipe de ce projet est formée de cinq membres. Chaque membre est un responsable d'une partie du projet, il doit repartir les tâches propres à sa partie pour que les autres membres puissent finir ces taches. La distribution et la gestion des tâches est faites sous pivotaltracker.

|Membres|Rôle|
|-----|------|
|Membre 1 | Responsable de la gestion de la base de donnés.|
|Membre 2 | Responsable de la partie côté serveur.|
|Membre 3 | Responsable de l'application mobile.|
|Membre 4 | Responsable de partie web.|
|Membre 5 | Responsable du système de pistage.|

# Pilotage du projet

## Estimations des charges et durées
La durée du projet est environ de 600 heures de travail. Il comprend le développement, la planification et la gestion. Ces heurs sont repartis également sur tous les membres de l'équipe. Chaque membre est garant à l'estimation des charges et de la durée de la partie dont il est responsable.
Le temps de délivrassions du projet est le début de mois de septembre 2016.

## Planification
Les exigences actuelles sont ceux décrits dans ce plan, tous changement sera effectuer sur ces exigences directement. 

## Suivi du projet
Le projet sera effectué suivant la méthode agile, et les tâches sont réparties et distribués sur pivotaltracker.
