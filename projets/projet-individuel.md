# Projet Individuel MGL7460-90 (Hiver 2020)

  * Auteur : Sébastien Mosser (UQAM)
  * Date de publication : Janvier 2020
  * Relecteurs : Mireille Blay-Fornarino (UCA), Philippe Collet (UCA)

## Objectifs pédagogiques

Dans ce projet individuel, vous êtes en chargé par votre hiérarchie de l’analyse
d’un logiciel légataire afin d’estimer le risque pour votre compagnie d’accepter
un projet de tierce maintenance applicative sur ce logiciel. Pour rendre cette situation réaliste, nous simulerons cette application légataire par une application _open-source_ accessible publiquement.

Il est a votre charge d’identifier la méthodologie à mettre en oeuvre pour mener
l’analyse de ce logiciel, de la mettre en oeuvre, et de livrer vos conclusions
vis à vis de la “maintenabilité” du logiciel étudié sous la forme d’un rapport
de synthèse.

## Contraintes

  - Le logiciel étudié doit être disponible sur une plateforme de gestion de
    version (_e.g._, GitHub, Gitlab) de manière publique. Vous êtes entièrement
    libre du choix du projet (_e.g._, langage, taille, ...), mais votre choix
    doit être validé avec l’enseignant.
  - Vous devez accompagner votre rapport de synthèse d’un dépôt de code contenant :
      - les scripts / chiffriers / programmes que vous avez développés pour mener votre analyse;
      - Les données brutes que vous avez collectés;
      - une explication montrant comment installer et utiliser les outils que vous avez réutilisés
  - Le rapport de synthèse doit être livré au format PDF, faire 15 pages maximum
    (page de garde et annexes incluses, police times 11, interligne simple), et
    répondre aux questions d’analyse décrites dans ce sujet. Faites attention à
    la lisibilité des figures (on doit pouvoir lire une version imprimée de
    votre travail).
  - Vos réponses aux questions peuvent être technique, sans tomber dans le
    point de detail. Un développeur lambda doit être capable de comprendre vos
    réponses.
  - Sur la base de vos réponses aux questions d’analyse, vous produirez une note
    de synthèse d’environ une page en conclusion de votre rapport. Cette note
    donnera votre recommandation sur l’état du logiciel analysé, à l’attention
    de votre hiérarchie. Votre recommandation finale doit être de haut niveau,
    et prendre un recul global sur l’application.

Une liste de projets est maintenue [ici](https://docs.google.com/spreadsheets/d/e/2PACX-1vSpgEDfd2atEU43n7IF-SQEbLDFIgCb80ea3_p9QV2bV5CJuVjrFFUoVqVh5RhNg9AXRo9d27XcjBfK/pubhtml) si vous êtes à cours d'idées.

## Cadre d'analyse de maintenance

Les thématiques suivantes ne sont pas une liste exhaustive. Vous ne devez pas
tout traiter dans votre projet. Il est de votre responsabilité d'identifier ce
qui a le plus de sens dans le cadre de votre étude.

Pour chaque question, vous êtes libre de choisir la représentation la plus
adaptée a votre projet. Par exemple pour la description de la modularité de
l’application, l’analyse d’un gros projet nécessitera un diagramme de composant
ou de paquetages, mais un projet de taille plus modeste pourrait utiliser un
diagramme de classe. Vous devez justifier vos choix d’outils d’analyse ainsi que
votre méthodologie.


### Dimension "Équipe de développement"

  1. Qui sont les développeurs principaux du projet ?
  2. L'équipe de développement est-elle stable ?
  3. Comment est répartie la paternité du code source dans l'équipe ?
  4. Comment les développeurs communiquent entre eux ?

### Dimension "Exigences"

  1. Comment le code source est-il tracé aux exigences ?
  2. Quelle est la vélocité de l'équipe de développement sur la maintenance corrective ?
  3. Quel est le volume d'exigence traité dans le projet ?

### Dimension "Architecture logicielle"

  1. Quels sont les composants principaux de l'application ?
  2. Comment est gérée la modularité de l'application ?
  3. Comment est documentée l'architecture de l'application ?


### Dimension "Code source"

  1. Comment qualifiez vous la _qualité_ du code source ?
  2. Quels outils de construction (p.-ex. `make`, `maven`) sont utilisés ?
  3. Quel modèle de branche est utilisé dans le développement du projet ?
  4. Dans quelle mesure la compilation du code est-elle reproductible ?
  5. A quel point le code est-il dépendant de bibliothèques externes ?

### Dimension "Tests"

  1. Quelles sont les méthodes de tests mise en place dans le projet ?
  2. Comment qualifiez vous la _qualité_ des tests mis en oeuvre ?
  3. Dans quelle mesure les tests sont-ils reproductible ?

### Dimension "Déploiement & Livraison"

  1. Quels outils d'intégration / déploiement continus sont mis en place ?
  2. Comment sont gérées les dépendances logicielle dans le projet ?
  3. Quelle méthodologie de publication (_releasing_) est mise en place ?

## Livrables

  - `L0` : Choix du sujet (en message direct sur Slack)
  - `L1` : Rapport intermédiaire.
    * Doit définir les questions qui vont être traitées
    * Doit répondre à un sous-ensemble de ces questions
    * Doit expliciter la méthode qui sera suivie et les outils envisagés pour répondre aux autres questions.
  - `L2`: Rapport de synthèse final.
    * Contient les corrections demandées suite à la rétroaction sur `L1`;
    * Répond aux questions identifiées, ou explique les changements s'il y en à eu;  
    * Contient la note de synthèse sur le logiciel


_Astuce_ : Plus votre rapport intermédiaire contient d'information, plus vous obtiendrez de rétro-action sur votre travail et pourrez préparer le livrable final dans de bonnes conditions.

## Critères d'évaluation

| Thème | Critère        | Poids |
| :---: | :---         | :---: |
| Rapport | Qualité rédactionnelle | 10% |
|   | Qualité de l'analyse  | 20%  |
|   | Couverture de l'analyse  | 10%  |
|   | Pertinence de la méthodologie  | 20%  |
| Code   | Réutilisabilité des outils développés  | 10%  |
|   | Qualité du code  |  5%  |
| Entretien    | Clarté de la discussion | 10%  |
|   | Recul sur les réponses aux questions  | 15%  |


### Pour le livrable `L1`

  * Comme il n'y a pas d'entretien, la note sur `/75` est ramenée à 100 par une règle de trois, arrondi au point le plus proche.
  * Si les critères d'évaluations sont les mêmes que pour `L2`, l'évaluation sera plus pointue pour le rendu final que pour le rendu intermédiaire.

### Pour le livrable `L2`

  * Vous devez vous inscrire pour une rencontre avec le professeur, qui aura lieu dans les deux dernières semaines du cours;
  * Cette rencontre sera une séance de questions réponse sur votre étude, pour aller plus loin et vous donner l'opportunité de defendre a l'oral vos travaux;
  * Il n'y a pas de présentation (au sens de Powerpoint ou assimiléee) a prévoir, il s'agit "simplement" d'une discussion.


## Sujets Choisis à cette session :

| Étudiant | Cas d'étude | Dépôt de code |
| :---: | :---: | :--- |
| Marc-André | `Krita` | [https://github.com/KDE/krita](https://github.com/KDE/krita) |
| Nasseredine | `Spring Initializr` | [https://github.com/spring-io/initializr](https://github.com/spring-io/initializr) |
| Gary | `Angular` |[https://github.com/angular/angular](https://github.com/angular/angular) |
| Cristina | `React` | [https://github.com/facebook/react](https://github.com/facebook/react) |
| Leonardo | `NGXS` | [https://github.com/ngxs/store](https://github.com/ngxs/store) |
| Simon | `Dolphin` | [https://github.com/dolphin-emu/dolphin](https://github.com/dolphin-emu/dolphin) |
| Gérald | `NodeRed` | [https://github.com/node-red/node-red](https://github.com/node-red/node-red) |
| Lilian | `Jenkins` | [https://github.com/jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) |
| Dionisie | `JHipster Generator` |[https://github.com/jhipster/generator-jhipster](https://github.com/jhipster/generator-jhipster) |
| Pape Tahyre | `Mockito` | [https://github.com/mockito/mockito](https://github.com/mockito/mockito)  |
|Jean-Pierre | `Wordpress` |[https://github.com/WordPress/WordPress](https://github.com/WordPress/WordPress) |
|Majed | `JUnit 5`| [https://github.com/junit-team/junit5](https://github.com/junit-team/junit5) |
| Alexandre | `MySQL-Server` | [https://github.com/mysql/mysql-server](https://github.com/mysql/mysql-server) |
| Nicolas | `Android Framework` | [https://github.com/aosp-mirror/platform_frameworks_base](https://github.com/aosp-mirror/platform_frameworks_base) |
| Jimmy |`Kafka`| [https://github.com/apache/kafka](https://github.com/apache/kafka) |
| Eric | `RxJS` | [https://github.com/ReactiveX/rxjs](https://github.com/ReactiveX/rxjs) |
| David | `Mockito` | [https://github.com/mockito/mockito](https://github.com/mockito/mockito) |

## Consignes de livraisons

  1. Ouvrez l'onglet _Projet Individuel_ du tableur [Index des travaux](https://docs.google.com/spreadsheets/d/1PA6Uln9ps2Egl5rbn3JykbsHT8GSjfVJKGrty7t44Tg/edit?usp=sharing)
  2. Editez la colonne "dépôt" en donnant l'URL du dépot Git **public** que vous avez créé pour le projet. Ce dépot doit contenir : 
      * Votre rapport au format PDF;
      * Les données brutes utilisée pour vos analyses;
      * Les outils que vous avez développé pour traiter les données, ou la documentation permettant de lancer les outils que vous avez réutilisés. 
  3. Le dépôt est cloné automatiquement à la date de remise. Tout rendu hors consignes ne sera pas considéré (et recevra la note de zéro).
