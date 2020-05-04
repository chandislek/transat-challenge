# transat-challenge
autonomous sailing across atlantic challenge

traversée atlantique automatisée à la voile
challenge transition énergétique du transport maritime


1) À propos du projet:

des acteurs majeurs ont présenté une voiture autonome. que diriez-vous de faire traverser l'océan atlantique à un voilier autonome, propulsé par le vent, piloté par le soleil?

toutes les connaissances et les technologies pour concrétiser cet exploit sont matures: maîtrise de l'énergie solaire, électronique embarquée, automatisation d'action mécanique, calcul décisionnel pondéré, capteur environnemental, communication sans fil, anticipation météorologique.

la transition énergétique du transport maritime est à la portée de nos mains; c'est le moment!


2) À quoi va servir le financement ?

apportons les modifications nécessaire à un navire de 30 m² de surface de voile cumulée, long de 24 pieds de l'étrave au safran, pour le rendre autonome :

captation de l'énergie solaire, mesures des paramètres environnementales, automate décisionnel de mission, motorisation des organes directionnels et propulsifs, outil de communication télémétrique de survie en milieu agressif.



3) À propos du porteur de projet:

passionné de voile, responsable de projet à alléa, je cherche une solution à mettre en oeuvre en consolidant les technologies, les connaissances et les expérimentations, disponibles tout autour de nous.

la transition énergétique a grandi tout le long de ma carrière, c'est une évidence que nos chemins sont liès!

4) À propos des spécifications techniques:

-la commande se fait par des treuils munis de frein pour empêcher le déroulement des écoutes sous la pression du vent dans les voiles; afin de limiter la consommation électrique, le génois et la grand voile sont auto-vireurs, sans avoir à modifier le réglages des voiles; les actionneurs ne se mettent en marchent que pour border, le déroulement en choquant se fait avec la force du vent qui est de 62kg max au près pour un vent de 16 noeuds soufflant dans une voile de 10m².
-les enrouleurs entraînés par des treuils munis de frein permettent de diminuer la surface des voiles selon la force du vent et le rail de grand-voile permet de réguler la gîte.
-pour assurer le réglage des écoutes de voiles et du rails de grand-voile, le calculateur récupère les informations de l'anémomètre, du speedomètre, de l'inclinomètre et du GPS, puis en fonction de l'allure (de l'angle au vent et du diagramme polaire du voilier) définit la position des écoutes afin de dévier de 10° degrés l'écoulement du vent (d'où l'importance de déterminer la direction du vent réel avec les capteurs), angle qui assure que les voiles ont une portance et qu'il n'y a pas de décrochement des filets d'air.

cette expérimentation de transport maritime écologique automatisée, avec une grand voile de 11,30m² et d'un Foc n°1 de 12,70m², avec un diagramme polaire qui donne 5 noeuds (2,5m/s) de vitesse de croisière, détecte les obstacles de surface avec une caméra en tête de mât.

les règles de navigation à la voile sont dans le cas de risque d'abordage:
-priorité au voilier à tribord amure; dont le vent vient de la droite de l'avancement (la voile est à babord).
-le voilier situé sous le vent par rapport à l'autre voilier, n'a pas la priorité dans le cas où les 2 sont tribord amure.

plusieurs réactions sont prises d'urgence par l'automate de navigation:
-obstacle à tribord et je suis tribord amure, je vire babord 90° degrés (largue)
-obstacle à babord et je suis babord amure, je vire tribord 90° degrés (largue)
-obstacle à tribord et je suis babord amure, je vire babord 90° degrés (face au vent)
-obstacle à babord et je suis tribord amure, je vire tribord 90° degrés (face au vent)

distance nécessaire pour réagir:
la direction du voilier est changée par l'angle du safran, selon le sens d'avancement, qui peut atteindre 30° degrés en 4s;
l'efficacité de la quille permet de virer à 90° sur une surface de mer équivalente à la longueur du navire de 7m50;
l'automate dédié à la détection d'image prend 5 secondes pour commander le nouveau cap au pilote automatique.
en tout, la distance minimale pour éviter un obstacle est de 30m.

traversée de l'Atlantique:
de Brest à Boston, il y a 65° degrés de longitude et 8° degrés de latitude à parcourir; 
à 5 noeuds la traversée se fait en plus de 27 jours avec les vents d'Ouest; 
à éviter le courant marin du Gulf Stream qui est de 2 noeuds dans le sens contraire.

le voilier navigue uniquement par le vent; l'électricité nécessaire à l'automate de navigation est fournie par le soleil; 
le virement de bord face au vent (virement vent debout) ou vent arrière (virement lof pour lof) se réalise sans consommer de courant électrique, excepté celui consommé par le pilote de barre franche; les actionneurs électriques des écoutes ne fonctionnent que pour changer l'allure au vent (aulofée ou abattée).

La veille est assurée par l'envoi des coordonnées GPS et d'un rapport technique, par satellite, régulièrement.

Les avaries sont classées par ordre du plus vital au moins vital:
-réduction de voilure
-maintien de l'allure par l'autopilote de barre franche
-capteur de vent (direction et force)
-navigateur traceur de route avec GPS
-AIS de surveillance de la circulation maritime
-réglage des voiles avec mesure de gîte et de vitesse relative (speedomètre)
-caméra tête de mât avec détection d'obstacle
-prévision météo et option de navigation
-caméra surveillance cockpit-cabine-local technique

cette expérimentation rentre dans un contexte de transition énergétique du transport maritime et du suivi des océans.

l'automate organise en autonomie sa navigation selon les conditions locales tout en respectant un couloir imposé, 
des points de passage, déterminé et communiqué à distance, par satellite.
le couloir pour cette traversée est entre la route Sud et la route Nord.

la technologie de détection d'obstacle en milieu urbain est utilisée pour ne pas être perturbée par les conditions météo.

le voilier sera détectable par AIS. tous navires naviguant dans cette zone maritime utilisent un récepteur AIS à minima.

le plan d'aménagement du pont et les matériaux utilisés pour le gréement sont déterminés pour des conditions en milieu agressif : 
absence de pièce offrant des surfaces hautes de prise aux vagues ou au vent, 
absence de bouts longs et détendus sans retenues,
absence de voiles molles et sans guidages, 

la surface des voiles et leur orientation au vent sont évaluées par l'automate en fonction des paramètres environnementaux, 
selon le diagramme polaire du voilier, pour réguler les tensions mécaniques et la propulsion éolienne, 
sans interruption pendant toute la durée de la traversée, quelque soit l'état de la mer, en toutes circonstances météorologiques.

l'automate embarqué à bord du voilier réalise les calculs qui lui permettent de prendre les décisions locales les plus stables, en prenant en compte les consignes imposées (destinations, prévisions météorologiques) et les dangers, selon un cycle déterminé, répété plusieurs fois par seconde:
-lecture des capteurs
-comparaison entre mouvement réalisé et commande
-vérifications des consignes imposées (destination, météo)
-calcul du cap à suivre
-vérification du dangers, des avaries
-commandes des voiles et du safran

les informations échangées par satellite concernent les consignes imposées et le rapport technique (dont la position GPS).

quand l'allure du voilier est conservée sans modification, la seule consommation d'électricité est celle des capteurs et du calculateur, correspondant à quelques 3 ampères; aucun actionneur n'est activé, pour maximiser l'autonomie et la robustesse du voilier.

en moyenne un panneau solaire de 175W de 1m² fournissant 70A par jour, permet d'assurer la consommation continue de 3A de l'électronique.
