# MGL7460: Réalisation & Maintenance de Logiciels

## Informations Générales

  * Équipe Enseignante :
    * Professeur : Sébastien Mosser (UQAM, [Site web personnel](https://mosser.github.io), [Groupe de recherche ACE](https://ace-design.github.io))
    * Laboratoires : Jean-Philippe Gélinas (SFL, Lévis), Jonatan Cloutier (SFL, Montréal)
  * Horaire du groupe `090`, session d'hiver 2020:
    * Cours : Jeudi, 15h00 - 18h00, _Tour Desjardins_
  * Communication :
    * Slack : [mgl7460-h20.slack.com](mgl7460-h20.slack.com)

### Objectif du cours

Sensibiliser les étudiants aux problématiques de réalisation et de maintenance du logiciel.

### Évaluation & Planning de rendus

**Les dates de remise s'entendent sur le fuseau horaire de Montréal, à 23:50 le jour de la date de remise. Tout rendu hors délai recevra la note de zéro (0). Les règles concernant le plagiat seront appliquées sans aucune tolérance.**

| Date(s)        | Travail à rendre               |  Poids |
| :---:          | :---                           | :---: |
| 19.01.20 | Choix du cas d'études individuel   | 0%  |
| 01.03.20 |  Projet Individuel - V1  |  20%  |
| 15.03.20 |  Projet Technique - MVP  |  20%  |
| 27.03.20 |  Rapport léger sur le projet technique  |  --  |
| 12.04.20 |  Projet Individuel - V2  |  40%  |
| 26.04.20 |  Projet Technique - Final |  20%  |

## Agenda des séances

En régime régulier, les cours ont lieu le jeudi, de 15h à 18h, dans les locaux de Desjardins.

| #Semaine | Cours (UQAM) | Atelier (SFL) |
| :---: | :---:   | :---    |
| 2  | [Leçon introductive: Réaliser, Maintenir et Modéliser du logiciel ?](./cours/1_intro.pdf) |  (Lab optionnel)  |
| 3  | [Gestion de versions, Tests](./cours/2_versions_tests.pdf)  |  --  |
| 4  |  --  | _Git, GitLab, GitLab CI_  |
| 5  | [Exigences, Scénarios d'acceptations](./cours/4_exigences_acceptation.pdf)  | --  |
| 6  | Déploiement continu, _Test-driven development_  | --  |
| 7  | --  |  _BDD, TDD_  |
| 8  | [Mesure Logicielle](./cours/7_mesure.pdf)  | _Sonarqube_  |
| 9  | _Semaine de relâche_  | --  |
| 10 | [Clean Code & Tests](./cours/9_cc_tests.pdf)  | Suivi projet(s) |
| 11 | [Visualisation pour la maintenance](./cours/10_visualisation.pdf)  |  Suivi projet(s)  |
| 12 | ~Présentation intermédiaire du Projet Technique~ |  ~idem~  |
| 13 | ~Leprechauns du Génie Logiciel~  |  ~Suivi projet technique~ |
| 14 | [Cours invité DevOps](./cours/13_DevOps.pdf), Pr Francis Bordeleau, ÉTS. ([Vidéo](https://meet.jit.si/UQAM-MGL-7460))|  [Suivi projet(s)](https://docs.google.com/spreadsheets/d/12DkwUvLIl6fEUw3t8X9-YCRnhtGXfI7hgFNcJD0bEgM/edit?usp=sharing)  |
| 15 | [Cours invité qualité](./cours/14_qualite.pdf), Pr Xavier Blanc, Univ. Bordeaux. ([Vidéo](https://meet.jit.si/UQAM-MGL-7460)) |  [Suivi projet(s)](https://docs.google.com/spreadsheets/d/12DkwUvLIl6fEUw3t8X9-YCRnhtGXfI7hgFNcJD0bEgM/edit?usp=sharing)  |
| 16 | [_Rencontres Projet Individuel_](https://docs.google.com/spreadsheets/d/12DkwUvLIl6fEUw3t8X9-YCRnhtGXfI7hgFNcJD0bEgM/edit?usp=sharing)  |  Suivi projet(s) SFL |
| 17 | [_Rencontres Projet Individuel_](https://docs.google.com/spreadsheets/d/12DkwUvLIl6fEUw3t8X9-YCRnhtGXfI7hgFNcJD0bEgM/edit?usp=sharing)  |  Suivi projet(s) SFL |


  * Énoncé des travaux pratiques :
    * [https://yakoi.gitlab.io/mgl7460/](https://yakoi.gitlab.io/mgl7460/)

## Travaux

  - Projet Individuel
    - [Mémoire de synthèse sur la maintenabilité d'un logiciel](./projets/projet-individuel.md)
  - Projet Technique :
    - [Mise en oeuvre d'un pipeline de déploiement continu](./projets/projet-technique.md)


## Barème

  - Le cours utilise la grille d'évaluation standard de l'UQAM au second cycle définie dans RESULTATS.
  - La note de passage est de 63/100, conformément à la grille du second cycle.
  - AMEAGEMENT COVID-19: ~*Attention*: une note inférieure à 60/100 sur le projet individuel fait échouer le cours, indépendamment de la note obtenue au projet technique.~ Le double seuil est abaissé à 50/100.

<div align="center">

![echelle de notes](./docs/echelle_M.png)

</div>

## Bibliographie & Références

### Cheat Sheet

  - Clean Code: [(pdf)](./docs/clean_code_cheatsheet.pdf)

### Articles scientifiques

  * _Enseigner la rétro-ingénierie, en s’interrogeant sur l’évolution du logiciel : retour d’expériences_
    * Mireille Blay-Fornarino, Sébastien Mosser, Xavier Blanc. CIEL 2017.
    * [Accès PDF](./docs/ciel17.pdf)
  * _On the Nature of Merge Conflicts: a Study of 2,731 Open Source Java Projects Hosted by GitHub_  
    * Gleiph Ghiotto, Leonardo Murta, Márcio Barros, and André van der Hoek. TSE18, ICSE19.
    * [Accès PDF](./docs/ghiotto.pdf)
  * _Practitioners’ Views on Good Software Testing Practices_
    * Pavneet Singh Kochhar, Xin Xiat, and David Lo. ICSE19 / _Software Engineering in Practice_
    * [Accès PDF](./docs/kochar19.pdf)
  * _State of mutation testing at Google_
    * Goran Petrovic, Marko Ivankovic
    * [Accès PDF](./docs/petrovic19.pdf)
  * _QuickREST: Property-based Test Generation of OpenAPI-Described RESTful APIs_
    * Stefan Karlsson, Adnan Causevic, and Daniel Sundmark. ICST20.
    * [Accès PDF](./docs/karlsson20.pdf)

### Livres d'enseignement

  * _Introduction to Software Design with Java_. Springer, 2019.
    * Martin Robillard (_McGill University_).
    * [Accès PDF SpringerLink via UQAM](https://link.springer.com/book/10.1007%2F978-3-030-24094-3)
  * _UML@Classroom_, Springer Verlag, 2015.
    * Martina Seidl, Marion Scholz, Christian Huemer & Gerti Kappel (_Université de Technologie de Vienne_).
    * [Accès PDF SpringerLink via UQAM](https://link.springer.com/book/10.1007%2F978-3-319-12742-2)
    * [Site web ressource (diapos additionelles)](http://www.uml.ac.at/en/)

### Livres professionels

  * _Clean Code_. Prentice Hall.
    * Robert Martin.
    * Disponible en bibliothèque (BU Sciences, cote `QA 76.76 D47 M38 .2009`)
    * _(Existe en version française: "Coder proprement")_
  * _Pragmatic Unit Testing_. The pragmatic programmers.
    * Jeff Langr, with Andy Hunt and Dave Thomas.  
    * Disponible en bibliothèque (BU Sciences, cote `QA 76.73 J38 L36 .2015`)
  * _Refactoring: Improving the Design of Existing Code_, Addison Wesley, 2018 (2nd edition)
    * Martin Fowler.  
    * Disponible en bibliothèque (BU Sciences, cote `QA 76.76 R42 F69 .1999`)
  * _Code as a Crime Scene_. The pragmatic programmers.
    * Adam Tornhill.  
  * _The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations_.
    * Gene Kim, Patrick Debois, John Willis, Jez Humble & John Allspawn.

## Règlement 18 sur les Infractions de nature académique

Tout acte de plagiat, fraude, copiage, tricherie ou falsification de document commis par un.e étudiant.e, de même que toute participation à ces actes ou tentative de  les commettre, à l’occasion d’un examen ou d’un travail faisant l’objet d’une évaluation ou dans toute autre circonstance, constituent une infraction au sens de ce règlement.

La liste non limitative des infractions est définie comme suit :

  * la substitution de personnes ;
  * l’utilisation totale ou partielle du texte d’autrui en le faisant passer pour sien ou sans indication de référence ;  
  * la transmission d’un travail aux fins d’évaluation alors qu’il constitue essentiellement un travail qui a déjà été transmis aux fins d’évaluation académique à l’Université ou dans une autre institution d’enseignement, sauf avec l’accord préalable de l’enseignante, l’enseignant ;
  * l’obtention par vol, manœuvre ou corruption de questions ou de réponses d’examen ou de tout autre document ou matériel non autorisés, ou encore d’une évaluation non méritée ;
  * la possession ou l’utilisation, avant ou pendant un examen, de tout document non autorisé ;
  * l’utilisation pendant un examen de la copie d’examen d’une autre personne ;
  * l’obtention de toute aide non autorisée, qu’elle soit collective ou individuelle ;
  * la falsification d’un document, notamment d’un document transmis par l’Université ou d’un document de l’Université transmis ou non à une tierce personne, quelles que soient les circonstances ;
  * la falsification de données de recherche dans un travail, notamment une thèse,  un mémoire, un mémoire-création, un rapport de stage ou un rapport de recherche.

Les sanctions reliées à ces infractions sont précisées à l’[article 3 du Règlement no 18](https://instances.uqam.ca/wp-content/uploads/sites/47/2017/12/REGLEMENT_NO_18.pdf) sur les infractions de nature académique.

Vous pouvez consulter sur le site [r18.uqam.ca](http://r18.uqam.ca) des capsules vidéos qui vous en apprendront davantage sur l’intégrité académique et le R18, tout en vous  orientant vers les ressources mises à votre disposition par l’UQAM pour vous aider à éliminer le plagiat de vos travaux.
