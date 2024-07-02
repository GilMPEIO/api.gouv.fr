---
title: API Répertoire Opérationnel des Métiers et des Emplois
tagline: Utiliser les référentiels d’emplois et de compétences
producer: France Travail
category: Public
is_open: 0 # -1 means API not open
account_link: https://francetravail.io/inscription
external_site: https://francetravail.io/data/api
partners:
  - FRance Travail
keywords:
  - Travail
  - Emploi
  - Marché du travail
  - Métier
  - Métiers
  - Compétences
  - ROME
  - AFPA
  - Mobilité professionnelle
contact_link: contact@francetravail.io
doc_tech_external: https://francetravail.io/data/contribuer-rome
datagouv_uuid:
  - 58da857388ee384902e505f5
themes:
  - Emploi
visits_2019: 1000
last_update: 02/08/2021
---

Le ROME (Répertoire Opérationnel des Métiers et des Emplois) est un ensemble de référentiels permettant de décrire les emplois et les compétences.
La version 4.0 est dynamique, elle sera actualisée tous les trimestres pour témoigner des évolutions du marché de l’emploi. C’est une donnée publique de référence.
Le ROME facilite la mise en relation entre l’offre et la demande d’emploi et accompagne les choix de mobilités professionnelles.

### A quoi servent les API du ROME ?

Ces API ont pour objectif de simplifier l'accès à l'information sur les emplois, au service de la mobilité professionnelle. Plus largement, elles visent à rapprocher les offres d'emploi des candidats.

### Données accessibles dans l'API

**API ROME 4.0 – Compétences**

L’API « ROME 4.0 - Compétences » donne accès au référentiel des compétences et des savoirs du Répertoire Opérationnel des Métiers et des Emplois.

Ce référentiel s’appuie sur une arborescence thématique à 5 niveaux :​

1.      ​Le Domaine de compétences est le premier niveau de la structure.

6 domaines de compétences composent l'architecture :​ 5 domaines de savoir-faire "techniques" et 1 domaine de savoir-faire et savoir-être "transverses"​.

2.      L’Enjeu (31). Il est le résultat de la combinaison entre les domaines de compétences et les bénéficiaires cibles (l’individu lui-même, son équipe, son entreprise, ses clients ou marchés, son territoire ou plus largement d’intérêt général). Un enjeu est rattaché à un seul domaine. Les enjeux sont utilisés pour la lisibilité de l’affichage des macro-compétences et contenus détaillés.​

3.      L’Objectif (83). Il couvre le champ d'action des macro-compétences et compétences rattachées. Il est déterminé par un verbe. Un objectif est rattaché à un seul enjeu. ​

4.      La Macro-compétence (507). Elle vise une maille plus décontextualisée et rassemble des contenus sur la base de ‘gestes professionnels’ proches ou similaires, indépendamment du métier ou du secteur d’activités. La macro-compétence est une maille de synthèse des compétences poursuivant le même objectif. Une macro-compétence est rattachée à un seul objectif. Elle est exploitée dans le rapprochement entre l’offre et la demande à France Travail.​

5.      La Compétence (6516). Elle désigne la capacité à agir dans une situation professionnelle donnée, en mobilisant et en combinant des ressources telles que :​

les savoirs (ce que je sais, ce que j’ai appris)
les savoir-faire (ce que je sais faire)
les savoir-être professionnels (comment j’agis et interagis)


**API ROME 4.0 – Métiers**

L'API comprend :

- Le code ROME et l’intitulé de la fiche.

- Le code RIASEC associé à chaque fiche.
Le R.I.A.S.E.C. est un acronyme constitué des initiales des 6 domaines d’intérêts professionnels de la typologie de Holland : Réaliste, Investigateur, Artistique, Social, Entrepreneur, Conventionnel. Les deux domaines, le majeur (en majuscule) et le mineur (en minuscule) qui caractérisent l’emploi, sont définis par des psychologues du travail de France Travail.

- Les autres emplois décrits dans les fiches (appellations synonymes et déclinaisons spécifiques de l’emploi) qui constituent le référentiel des appellations d’emploi.

Le référentiel des appellations d’emploi est composé de:

609 métiers (et plus de 11 500 appellations) ​
110 domaines professionnels ​
14 grands domaines. ​
6516 compétences structurées ​
6 domaines de compétences
31 enjeux, 83 objectifs
507 macro-compétences


**API ROME 4.0 – Contextes de travail**

Les contextes de travail précisent l’environnement de travail au sein duquel l’emploi est réalisé aussi bien d’un point de vue matériel, organisationnel que relationnel.

Ils sont classés en 6 catégories et 125 rubriques :

Conditions de travail et risques professionnels
Horaires et durée du travail
Lieux et déplacements
Publics spécifiques
Statut d'emploi
Types de structures

**API ROME 4.0 – Fiches métiers**

Le jeu de données de l’API ROME 4.0 – Fiches métiers fournit les informations utiles à la reconstitution d’une fiche métier du Répertoire Opérationnel des Métiers et des Emplois :

Cette API vous permet d’identifier, pour chaque fiche :

Les groupes de compétences mobilisées : les compétences sont classées et ordonnées par enjeu,
Les groupes de savoirs : les savoirs sont classés et ordonnés par catégorie de savoir.
Cette API s’utilise en complément de l’API ROME Métiers. 

 
### Les modalités d'exposition du ROME
[Cette page](https://francetravail.io/data/contribuer-rome) propose différentes modalités d’exposition du ROME 4.0 : L'utilisation des API vous permet d'intégrer directement le ROME dans vos applications et vous garantit l'utilisation d'une donnée mise à jour en temps réel. Les 4 API du ROME vous donnent accès aux différents référentiels qui constituent le ROME (emploi, compétences, contexte de travail, fiches métiers).

D’autres API de dialogue avec le ROME basées sur l'intelligence artificielle sont également à votre disposition. Si vous souhaitez utiliser les données du ROME sans passer par une API, vous pouvez directement accéder aux fichiers des référentiels ROME en Open Data.
