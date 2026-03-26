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

## Le fil conducteur

Tout au long du programme, un fil conducteur était manifeste : la profession du test se confronte à des systèmes qui ne se comportent jamais deux fois de la même manière. Les tests traditionnels réussi/échoué ont été conçus pour du logiciel déterministe. Les systèmes déployés aujourd'hui — des agents pilotés par LLM à la détection de médias synthétiques — exigent de nouvelles approches : mesure statistique, garanties probabilistes et cadres de gouvernance capables de gérer l'incertitude.

Le Swiss Testing Day 2026 a montré que la profession en est consciente. La question est maintenant de savoir à quelle vitesse les outils et les pratiques suivront.
