---
layout: post
title: "Le registre des taxis : comment une API permet d'adapter la mission de
  service public des taxis au numérique"
date: 2021-05-05
authors:
  - olivier.maffre
categories: general
tags: transport
image: /img/posts/2021-05-03-letaxi-servicepublic.jpg
excerpt: Le numérique a transformé nos vies, bouleversé nos usages, notre
  manière de consommer des biens et des services ; il est donc logique qu’il
  modifie sensiblement l’action publique, en lui donnant des moyens d’agir sur
  la sphère virtuelle, à travers des infrastructures publiques numériques. Cet
  article a pour but de montrer comment l’API le.taxi s'intègre dans cette
  logique, dans une vision de mutabilité du service public.
---



Le numérique a transformé nos vies, bouleversé nos usages, notre manière de consommer des biens et des services ; il est donc logique qu’il modifie sensiblement l’action publique, en lui donnant des moyens d’agir sur la sphère virtuelle.
Cette philosophie, c’est celle de [beta.gouv](http://beta.gouv.fr). Quel lien avec les taxis ? [Comme l’écrivait en 2019](https://medium.com/@ishanbjw/l%C3%A2ge-des-infrastructures-num%C3%A9riques-publiques-affdd4fc4558) Ishan Bhojwani de l'équipe beta.gouv.fr, en ce qui concerne la mobilité, l’âge des infrastructures publiques numériques est venu. Cet article a pour but de montrer comment l’API [le.taxi](https://le.taxi/) s'intègre dans cette vision, dans une logique de mutabilité du service public. 


**Une API, pour quoi faire ?**

Le.taxi, c’est une passerelle numérique entre les chauffeurs de taxis et les applications clients : à travers les applications qu’ils utilisent au quotidien, et qui sont partenaires de l’API, les chauffeurs sont visibles sur des applications clients d’information mobilité (en plein essor avec le développement des app type “Mobility as a service”) lorsqu’ils sont à la recherche de clients (en "maraude"). Ils peuvent être “hélés numériquement” par les utilisateurs de ces applications, sans frais d’approche et dans un rayon de quelques centaines de mètres. 


**Le taxi, un service public de transport un peu particulier**

Dans la galaxie des services publics de mobilité, le taxi occupe une place particulière, et  sa qualification de “service public” est souvent confuse. D’abord, le fait qu’il s’agisse d’un service assumé par une personne privée (souvent un artisan), et que le prix soit réglementé sans qu’il y ait pour autant généralement de financement public le distingue de nombreux autres services publics (au premier rangs desquels les transports en commun, dont la subvention peut dépasser 70 ou 80% du coût total). Dans certains cas, les taxis opèrent d’ailleurs des missions de service public de transport de façon déléguée (transport à la demande et transport scolaire), ce qui fait déjà d’eux des alliés des réseaux de transport public. Par ailleurs, à travers les conventions dont ils disposent avec l’assurance maladie, les taxis gèrent le transport de malades assis partout en France : en 2019, cette activité représentait la moitié du chiffre d'affaires total des taxis en France (environ 2 milliards d’euros). Cette grande variété de pratiques, qui a évolué au fil du temps, permet de comprendre l’impressionnant maillage national des presque 60 000 taxis (à l’inverse, les VTC sont concentrés dans les grandes métropoles). 

**Mais… en quoi le taxi en “maraude” est-il un service public ?**

Pour opérer, un chauffeur de taxi doit disposer d’une autorisation de stationnement (communément appelée licence) délivrée par les communes ; cette licence délimite la zone sur laquelle le chauffeur est autorisé à prendre des clients. Cela permet de réguler l’offre (la commune délivre de nouvelles licences au fil des besoins). En contrepartie de leur licence, les taxis ont des droits et des obligations : le droit de circuler à la recherche de clients et de les prendre en charge sur la voie publique (c’est le “monopole de la maraude”), mais aussi l’obligation de prendre en charge tout client le demandant (un taxi n’a le droit de refuser un client que sous certaines conditions). En ce sens, on considère que les taxis ont un rôle de service public, assumé par une personne privée mais contrôlé par la puissance publique. 


**L’irruption des VTC, le numérique, et les taxis.** 

L’irruption des VTC est une conséquence de la diminution soudaine des coûts de mises en relation offerte par le numérique : les taxis, dont les courses étaient distribuées depuis longtemps par des centrales radios ou grâce à une organisation de l’espace physique spécifique (maraude physique, stations de taxis) ont vécu une transformation radicale de la façon dont les clients pouvaient accéder à une voiture avec chauffeur. Cet essor est évidemment accompagné d’un contexte juridique, économique, social qui lui est favorable ; mais sans le numérique, cette transformation n’aurait tout simplement jamais eu lieu. Les coûts de transactions resteraient élevés car le passage par un téléopérateur serait une condition d’accès au service. La valeur serait donc captée par celui qui optimise la distribution des courses via ses téléopérateurs, là où le numérique place aujourd’hui cette valeur dans les mains de ceux qui produisent les interfaces numériques susceptibles d’attirer le plus de clients possibles (et d’utiliser l’algorithme le plus efficace possible pour distribuer les courses). 

Cette évolution des usages est désormais profondément ancrée dans les pratiques. Connaissez-vous autour de vous des personnes qui, dans les grandes métropoles, préfèrent téléphoner à une centrale pour commander un taxi plutôt que d’utiliser une application VTC ? Avouons-le, cet usage est de moins en moins fréquent... Parce qu’elles étaient issues de structures innovantes (des startups) qui ont su avant tout le monde détecter et prévoir les bouleversements que les smartphones allaient introduire dans les usages, ces applications ont connu une très forte croissance. C’est ainsi que la plupart des urbains commandent des VTC malgré eux, quand bien même ils seraient en désaccord avec le modèle proposé par les plateformes. La majorité des centrales de taxis l’ont d’ailleurs bien compris, en investissant dans des outils numériques leur permettant d’optimiser la distribution des courses en réservation. Ces investissements sont sources de renouveau pour certaines flottes, qui voyaient leur chiffre d’affaires progresser avant la crise sanitaire. 

C’est dans ce contexte que s’inscrit la “maraude électronique”. Aux côtés des innovations développées par les opérateurs de taxis, la maraude électronique vient en effet proposer une brique qui élargit la mission de service public des taxis, sans pour autant empiéter sur le rôle des opérateurs privés.

**Le service public de maraude électronique** 

Les différents contextes dans lesquels opèrent les taxis ont pour conséquences l’application de régimes juridiques différents. En ce qui concerne la maraude, les chauffeurs sont autonomes dans leur organisation (il n’y a pas d’intermédiaire, puisque le client accède directement au véhicule). Les courses en réservation, qu’il s’agisse de réservation immédiate ou préalable, nécessitent quant à elles d’avoir recours à un opérateur, qui réceptionne et distribue ces courses, et facture éventuellement le chauffeur pour cela. C’est tout le travail des centrales radio, qui existent depuis les années 1950 à Paris. 
Que change le numérique ? En abolissant les coûts de mise en relation, il permet de voir à travers un smartphone ce que l’oeil nu ne peut pas visualiser. Pour être visible dans l’espace public, un taxi a l’obligation de se doter d’un lumineux, qui indique sa disponibilité (vous savez, la petite lumière verte que vous scrutez avec angoisse dans la rue en fin de soirée quand la batterie de votre smartphone est à plat). La maraude électronique duplique cette logique en l’appliquant au numérique, en offrant la possibilité aux usagers d’héler numériquement le taxi le plus proche, à travers les outils de géolocalisation utilisés par les taxis.

Cette évolution répond pleinement à la logique d'adaptabilité du service public ([un des trois grands principes](https://www.vie-publique.fr/fiches/20223-la-notion-de-service-public) constitutifs du service public). Pour quelle raison la puissance publique devrait-elle circonscrire son action au monde physique ? Le numérique doit-il être la chasse gardée d’acteurs privés en quête de rentabilité ? Dans le cas présent, l’acteur public est pleinement légitime : sa nécessaire hauteur de vue ou son indispensable impartialité ne saurait excuser toute immobilité. Il s’agit ni plus ni moins que d’adapter le service public de maraude pour mieux correspondre aux nouveaux usages créés par le numérique. Cette évolution, qui de prime abord peut sembler concurrentielle avec l’activité de réservation immédiate, est en réalité une extension logique et justifiée d’un service public qui nécessite la mutualisation d’une grande densité de taxis pour pouvoir fonctionner efficacement. Imaginez que le lumineux ne soit que facultatif ; une partie importante des taxis n’aurait jamais investi dans cet outil, et l’action d’héler un taxi aurait fini par disparaître à mesure que les taxis seraient devenus invisibles au milieu de la circulation. 
En s’adaptant à cette évolution, les taxis auront donc l’opportunité d’exercer pleinement le monopole de la maraude qui leur revient : permettre à tous les clients potentiels de les héler via un smartphone. Pour les taxis, cette nouvelle possibilité ouvre donc un nouveau marché.


**Les taxis au service de la mobilité durable**

La maraude électronique, en rendant visibles les taxis disponibles à proximité immédiate, permet d’élargir la zone de pertinence de la maraude, par exemple pour la périphérie des villes. Avec presque 60 000 taxis en France, ce nouvel outil permettra de mobiliser de façon inédite un réseau d'artisans, dont la force repose sur sa capacité à couvrir l’ensemble du territoire national. Différentes perspectives peuvent être imaginées en cas de succès de ce projet, dans l’objectif de faire des taxis un nouveau service de mobilité ; taxis partagés, ligne de taxis en complément des bus, etc. Tous ces nouveaux usages correspondent bien à une logique multimodale, largement favorisée par les acteurs publics ces dernières années, dans laquelle la voiture individuelle est remplacée par différents modes, dont la pertinence est à évaluer en fonction des configurations du territoire, des contextes, des besoins, etc. La dispersion des activités sur les territoires laisse penser que le besoin de transport individuel va rester fort : s’il pourra progressivement être remplacé par des bus, trains, vélos ou trottinettes à de certains endroits, il restera de nombreux besoins non satisfaits, sur lesquels les taxis pourraient judicieusement venir en appui. L’intermodalité train + taxis pourraient par exemple avoir beaucoup de sens. Remplacer la voiture individuelle par du transport en commun et un peu de taxi, c’est viser un optimum dans lequel tout le monde est gagnant !

Pour tous ces nouveaux usages, la “mise à jour” du logiciel “service public” est indispensable. Comprendre et suivre les nouveaux usages, repenser les objectifs et le cadre d’action des services publics, accompagner les acteurs qui les produisent : au coeur de leur mission, beta.gouv.fr et la DGITM créént à travers l’API le.taxi une infrastructure publique numérique particulièrement novatrice.