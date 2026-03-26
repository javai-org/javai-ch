---
title: "Conformité et IA au premier plan du Swiss Testing Day 2026"
date: 2026-03-26
description: "Le Swiss Testing Day 2026 a placé la conformité de l'IA et les tests non déterministes au centre des débats, avec des intervenants issus de la banque, de la gouvernance et du génie logiciel."
summary: "Le Swiss Testing Day 2026 a rendu une chose évidente : conformité et IA ne sont plus des conversations parallèles. De la keynote de Bertrand Meyer sur la vérification logicielle à une intervention remarquable sur l'inutilité de l'IA pour la conformité — et son caractère indispensable —, la conférence a montré que le test des systèmes non déterministes est le défi majeur des professionnels de la qualité aujourd'hui."
featured_image: "images/bertrand-meyer.jpg"
featured_image_alt: "Bertrand Meyer au Swiss Testing Day 2026"
featured_image_caption: "Software Correctness Authority Bertrand Meyer"
---

Le Swiss Testing Day 2026, qui s'est tenu à Zurich le 26 mars, a réuni testeurs, ingénieurs qualité et professionnels de la conformité pour une journée de conférences et de panels centrés sur une question dominante : que se passe-t-il lorsque l'IA s'invite dans des systèmes qui doivent être fiables, auditables et corrects ?

## La correction logicielle face au non-déterminisme

La keynote d'ouverture de Bertrand Meyer — pionnier du design-by-contract et du langage Eiffel — a donné le ton. Meyer a abordé un large éventail de sujets, mais n'a cessé de revenir à une idée centrale : prouver que le logiciel fait ce qu'il promet. Les grands modèles de langage (LLM), avec leur non-déterminisme inhérent, ont rendu ce défi plus difficile, pas plus simple.

Meyer a souligné que la performance des fonctionnalités stochastiques — en particulier les LLM — doit être *mesurée*, car un simple verdict réussi/échoué ne suffit pas. Il n'est toutefois pas entré dans le détail du *comment*, réitérant plutôt sa conviction de longue date : la correction doit être intégrée au logiciel dès sa conception.

Il a conclu sur une note optimiste, affirmant que le besoin d'ingénieurs logiciels compétents ne disparaîtra pas, même si leurs outils évoluent. Le code généré doit toujours être vérifié, et la compréhension humaine du code reste essentielle.

## La stratégie de test n'est pas une liste d'objectifs

Iosif Itkin a invité le public à réfléchir soigneusement à ce que signifie réellement une stratégie de test — et ce qu'elle n'est pas. Ce n'est pas une liste d'objectifs. Ce n'est pas non plus la même chose que l'assurance qualité, qui requiert un état d'esprit fondamentalement différent.

S'appuyant largement sur l'ouvrage *Good Strategy/Bad Strategy*, Itkin a livré un rappel précieux : les organisations qui prennent l'IA au sérieux doivent concevoir leur stratégie de test de manière délibérée, et non la laisser émerger par hasard.

## Les tests agentiques portent déjà leurs fruits dans la banque

Une équipe du secteur bancaire suisse a présenté « Avalon », un système à base d'agents qui génère des données de test synthétiques. Bien que la présentation soit rapidement entrée dans les détails du produit, le message clé était clair : il s'agit d'une application agentique sophistiquée qui produit déjà des gains de productivité mesurables. Le système fonctionne de manière transparente, affichant les interactions LLM et les appels d'outils en temps réel dans son interface.

## L'intervention conformité de la journée

La session la plus marquante fut celle de Nick Gushchin, *Why AI Is Useless for Compliance …and Why You Still Need It*. Gushchin, AI Transformation Manager, a présenté une approche structurée de la gestion des risques liés à l'IA à travers une matrice probabilité-impact — un cadre éprouvé dont l'importance, a-t-il souligné, n'est pas moindre à l'ère de l'IA.

Sa question centrale — comment quantifier la dimension « probabilité » pour des systèmes non déterministes — est précisément le défi que les frameworks de tests probabilistes cherchent à résoudre. C'était la première intervention de la conférence à affronter explicitement le problème du test de systèmes dont les résultats sont intrinsèquement variables.

Pas de battage médiatique, pas de discours vague — juste des recommandations pratiques et solides pour quiconque est responsable des tests et de la fiabilité dans des environnements pilotés par l'IA.

## Définir la qualité dans une décennie dangereuse

Le panel de l'après-midi a réuni Bertrand Meyer, Elmar Jürgens et Marcel Gygli, modéré par Anne-Lea Marte, autour d'une question d'apparence simple : dans un monde où les systèmes apprennent, comment définir la qualité ?

Les réponses ont immédiatement divergé. Gygli a défini la qualité en fonction de ce que l'utilisateur obtient. Jürgens a nuancé : pour du logiciel grand public, peut-être — mais les systèmes critiques exigent davantage. Meyer a adopté la vision la plus large, insistant sur le fait que la qualité est multidimensionnelle, qu'elle se mesure aux yeux de toutes les parties prenantes et qu'elle doit être maintenue dans le temps.

Sur la question de la vitesse, les panélistes se sont montrés prudents. Jürgens a mis en garde contre un compromis si la génération de code dépasse la génération de tests. Gygli a posé une question plus incisive : si 90 % du code généré est correct mais que les 10 % restants sont extrêmement difficiles à tester ou à déboguer, le gain de vitesse apparent pourrait être illusoire.

La discussion s'est tendue sur la responsabilité. Lorsqu'un système d'IA cause un préjudice, qui est responsable ? Jürgens a été catégorique : ceux qui ont créé le logiciel. Meyer a averti que le battage médiatique autour de l'IA comme son rejet sont tous deux dangereux, et que les décideurs se laissent trop facilement emporter par l'enthousiasme. Tous trois ont convenu que l'éducation et la réglementation sont essentielles pour maintenir les garde-fous humains.

Interrogés sur ce qui relève de l'absurde dans l'industrie, les panélistes n'ont pas mâché leurs mots. Meyer a pointé le fait de confier le contrôle aux agents avec les humains en secours. Gygli a ciblé le vibe coding. Jürgens a qualifié la plupart des approches de mesure de la productivité de dénuées de sens.

Sur leurs souhaits pour l'avenir, les panélistes ont convergé vers la réglementation. Gygli a réclamé une réglementation utilisable reflétant les besoins réels de la société. Meyer — plaisantant que « l'Amérique innove, la Chine copie, l'Europe réglemente » — a exprimé l'espoir de voir davantage de preuves mathématiques dans les tests. Jürgens espérait que Meyer ait raison, tout en notant que les méthodes formelles restent limitées en pratique.

## Quand le code généré ne peut pas être testé

Jonas Hermansson a partagé un retour d'expérience sans détour sur le développement logiciel entièrement réalisé par des agents IA. Son équipe utilise désormais plusieurs équipes d'agents aux rôles distincts — frontend, backend, base de données — et déploie deux fois plus d'agents de test que d'agents de développement.

Les leçons ont été durement acquises. Les premières expériences de code généré par vibe coding ont produit des solutions pratiquement impossibles à tester. Une fonctionnalité de connexion générée contenait un bug lié à une exigence ambiguë. Un wrapper QA testant l'intention des exigences jusqu'au produit final a tout de même manqué des bugs de concurrence. Finalement, l'équipe a réintroduit les tests manuels comme vérification finale — coûteux, mais nécessaire.

La révélation la plus frappante : l'équipe de Hermansson ne maintient plus du tout le code. Lorsqu'un changement est nécessaire, le code est régénéré de zéro. Un workflow radical qui soulève autant de questions qu'il en résout.

## La keynote de clôture : un appel à la pensée statistique

Robert Sabourin — universitaire et praticien chevronné du test — a livré une keynote de clôture qui a transformé le courant d'inquiétude de la conférence en opportunité. Il a repris le ton d'alerte que les organisateurs avaient délibérément choisi, en le contrebalançant par un message positif sur les opportunités commerciales liées au test des systèmes pilotés par l'IA.

{{< figure src="images/test-oracle.jpeg" alt="Diapositive sur les oracles de test probabilistes de la keynote de clôture de Robert Sabourin" caption="Robert Sabourin on the need for experiments and probabilistic testing" >}}

Plus significatif encore pour les thèmes de cette conférence, Sabourin a plaidé explicitement pour les tests probabilistes. Il a exhorté les testeurs à développer une pensée statistique, arguant que les services stochastiques doivent être testés de manière probabiliste — et non avec les verdicts binaires réussi/échoué hérités du logiciel déterministe. Une conclusion parfaitement adaptée à une journée qui avait tourné autour de cette idée sans toujours la nommer directement.

## Le fil conducteur

Tout au long du programme, un fil conducteur était manifeste : la profession du test se confronte à des systèmes qui ne se comportent jamais deux fois de la même manière. Les tests traditionnels réussi/échoué ont été conçus pour du logiciel déterministe. Les systèmes déployés aujourd'hui — des agents pilotés par LLM à la détection de médias synthétiques — exigent de nouvelles approches : mesure statistique, garanties probabilistes et cadres de gouvernance capables de gérer l'incertitude.

Le Swiss Testing Day 2026 a montré que la profession en est consciente. La question est maintenant de savoir à quelle vitesse les outils et les pratiques suivront.
