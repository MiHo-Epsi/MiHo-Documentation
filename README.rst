===================
Cahier des charges
===================
Equipe
--------
Le projet est séparé en 2 équipes bien distinctes, une équipe back-end composée de :

- Mélinda Berquier (I4 Atos)
- Jordy Barre (I4 Atos)
- Maxime Pruvost (I4 Atos)
- Julien Delissenne (I4 Atos)

et une équipe front-end composée de :

- Justine Moreau (B3 A)
- Sullivan Delaby (B3 A)
- Jeremy Thery (B3 A)

Contexte et présentation du projet
-----------------------------------
Il s’agit du développement d’un miroir connecté qui offre une expérience utilisateur innovante destiné aux clients hôteliers en priorité. Le miroir sera principalement réalisé sous forme de “Flat Design”.

Il permet d’avoir des détails sur:

- Le menu du restaurant de l’hotel
- L’environnement qui entoure les clients afin de pouvoir profiter au mieu de leur séjour touristique comme ils le désirent par exemple les endroits à visiter, comme le SPA, etc…

Plusieurs possibilités seront proposées :

- Le mode **“visiteur”** : Le miroir propose diverses activités ou restaurants aux alentours de l'hôtel
- Le mode **“travail”** : Le miroir propose les diverses activités et la carte de restauration de l’hôtel, mais aussi les différents évènements éphémères (ou séminaires) via le flux twitter de l’hôtel 
- Le mode **“voyage organisé”** : Le miroir propose les diverses activités en adéquation avec l’agence de voyage choisie

Analyse de l'existant
-----------------------
Des tas de miroirs connectés sont proposés sur le marché actuel, et cela passe du simple miroir statique, aux miroirs réagissants aux sons.

Ce que nous proposons, est un miroir connecté avec détecteur de mouvements également avec  des fonctionnalités prévues spécialement pour le milieu hôtelier, une des fonctionnalités clés, par exemple, est la création de deux interfaces réalisée selon la raison pour laquelle le client est au sein de l'hôtel (loisir ou travail) ainsi que l’affichage de la météo.

L’interface travail proposera les séminaires et divers événements qui serait susceptible d'intéresser le client en fonction de son métier, l’interface loisir quant à elle, proposera des activités pour se reposer et profiter de son séjour, telles que des visites guidées etc…

Actuellement, en hôtellerie, l’hôtelier s’occupe de la majorité des tâches administratives telles que la réception des clients (physique ou téléphonique), grâce à notre miroir, il en sera déchargé car le miroir contiendra des informations importantes à propos de l'hôtel ou de ses menus.

Objectif du projet
-------------------
Diminuer l’empreinte écologique en utilisant un support intelligent et ergonomique avec des gestes simples et intuitifs.
Obtenir le menu de restauration à jour en temps réel ainsi que d’autres fonctionnalités (telles que des informations) ce qui permet donc à l'hôtel de renseigner toutes les activités qu’il propose (évènements tels que des soirées, etc…)
En plus des fonctionnalités proposées par notre miroir, l’hôtelier se voit décharger de certaines tâches, comme l’annonce du menu au téléphone ou l’annonce des activités présentes au sein de l'hôtel.

Périmètre du projet
--------------------
Le projet vise un certains type de périmètre malgré les larges choix possibles avec ce type de système. Nous visons les clients d’hôtellerie de type business 3 étoiles minimum hors hôtel économique, le miroir sera intégré en phase de test dans chaque chambre de chaque catégorie de budget (suite, chambre individuelle, chambre standard, double) afin de récolter des informations nous permettant de placer au mieux notre miroir, dans les catégories adéquates.

Un partenariat avec une entreprise locale spécialisée dans la domotique sera concrétiser pour la production de nos miroirs connectés

Description fonctionnelle des besoins
--------------------------------------
L’utilisateur peut utiliser le miroir pour s’informer de la carte de restauration de l’hôtel par exemple, ainsi que ses activités. Mais aussi tout ce qui se trouve autour de l’hôtel.

+------------------------+------------------------------+
| Cas d'utilisation      | Descriptif                   |
|                        |                              |
+========================+==============================+
| Afficher les diverses  | Renseigner les clients sur   |
| activités en fonction  | les activités a faire :      |
| de la venue du client  |                              |
|                        | 1. Si ce dernier vient dans  |
|                        | le cadre du travail, des     |
|                        | activités interne a l'hotel  |
|                        | lui sera proposé tel que le  |
|                        | SPA ainsi que la restauration|
|                        | ,à l’inverse si le client    |
|                        | vient pour les vacances, des |
|                        | activités externes telles que|
|                        | des visites guidées seront   |
|                        | proposés                     |
|                        | Ces activités seront         |
|                        | disponibles sur notre        |
|                        | miroir via un swipe.         |
+------------------------+------------------------------+
| Afficher la météo      | Affiche le temps, la force   |
|                        | du vent et la température    |
|                        | sur le menu de base pour     |
|                        | tous les clients,  même lors |
|                        | du mode veille               |
+------------------------+------------------------------+
| Afficher l'heure       | Affiche l’heure sur le menu  |
|                        | principal, même lors du mode |
|                        | veille                       |
+------------------------+------------------------------+
| Fil d’actualité        | Affiche les événements de    |
| (Twitter)              | l’hôtel via le réseau social |
|                        | twitter sur le menu principal|
+------------------------+------------------------------+
| Affiche le menu du     | Le menu du restaurant sera   |
| restaurant de l’hotel  | accessible via un swipe pour | 
|                        | les clients professionnels et|
|                        | pour les particuliers qui le |
|                        | désirent                     |
+------------------------+------------------------------+
| Afficher des publicités| Lors de la mise en veille du |
| sur l'ecran de veille  | miroir, des publicités seront| 
|                        | visibles selon l'interface : |
|                        |                              |
|                        | 1. Interface travail :       |
|                        | Réduction pour le SPA, bonnes|
|                        | pratiques de l'hotel, avec   |
|                        | des conseils pour l'écologie |
|                        | (par exemple,laisser les     |
|                        | serviettes a terre pour      |
|                        | qu'elles soient lavées) ainsi|
|                        | que les horaires du          |
|                        | restaurant                   |
|                        |                              |
|                        | 2. Interface Loisir :        |
|                        | Les publicités seront plus   |
|                        | tournées vers l'éco-tourisme |
|                        | (eteindre les lumieres quand |
|                        | personne n'est dans la piece,|
|                        | pratique des serviettes..)   |
|                        |                              |
+------------------------+------------------------------+

Notre application à détection de mouvement, contiendra 2 mouvements avec possibilité d’évolutions:

- le swipe à gauche
- le swipe à droite
- le swipe bas et haut dans une prochaine release

La distance des mouvements pouvant être détecté par le miroir est à déterminer selon la librairie utilisée. Nous aurons également un retour de mouvements afin d’avoir un calibrage parfait du mouvement ainsi qu’une compréhension du geste.

Il y aura un mode veille lors d’une inactivité prolongée de l’utilisateur.

Pour les publicités internes et les annonces,nous aurons un carrousel,qui les fera défiler.
Exemple: pour le mode travail on aura une publicité pour profiter de 20% sur le SPA entre 18h et 20h et pour l’interface loisir, une annonce qui pourrait également être pour l’interface travail, renseignera le client sur les bonnes pratiques de l'hôtel comme par exemple, si le client laisse ses serviettes sur le sol, elles seront à laver par le personnel de chambre, cela évite de laver toutes les serviettes.

Délais
--------
Le délai est fixé pour la fin de l’année scolaire. (fin juin, début juillet)

============
Conception
============

Description structurelle du projet
------------------------------------

+------------------------+------------------------------+
| Principaux constituants| Caracteristiques techniques  |
|                        |                              |
+========================+==============================+
| Raspberry Pi 4         | Permet l'usage de            |
|                        | l'application sur le miroir  |
|                        |                              |
+------------------------+------------------------------+
| Moniteur de 80cm et    | Permet d'afficher            |
| miroir sans teint      | l'application a travers un   |
|                        | effet miroir                 |
+------------------------+------------------------------+
| Module de caméra (11MP)| Utilisé pour la détection de |
|                        | mouvements                   |
|                        |                              |
+------------------------+------------------------------+


Description technique du projet
---------------------------------

+-----------------+-------------------------------+
| Langages utilisés                               |
+=================+===============================+
| Front-end       | Angular                       |
+-----------------+-------------------------------+
| Back-end hotel  | NodeJS                        |
|                 | API (meteo, twitter...)       |
+-----------------+-------------------------------+
| Back-end        | API JS                        |
| mouvement       |                               |
+-----------------+-------------------------------+


Nous avons choisis les langages NodeJS et Angular pour les compétences des personnes de l’équipe, NodeJS sera un serveur local temporaire et par la suite un serveur distant, au sujet de la base de données, nous utiliserons SQL car le flux de données n’est pas trop important, nous utiliserons également Sequelize en tant qu’ORM.
