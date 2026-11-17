# ShopSecure --- Analyse des risques SSI

**Projet personnel \| GRC · Gestion des risques cyber · EBIOS Risk
Manager**

Comment structurer une analyse des risques SSI pour une entreprise
e-commerce fictive, prioriser les risques métier et proposer un plan de
traitement concret ?\
C'est l'objectif de ce projet réalisé autour de **ShopSecure**, une
entreprise fictive de commerce en ligne.

> Ce dépôt présente une étude pédagogique et un cas fictif. Les
> constats, scénarios, cotations et décisions proposés ne constituent
> pas un audit réel ni une preuve de conformité.

## Le projet en bref

ShopSecure représente une entreprise e-commerce de **85
collaborateurs**, environ **50 000 comptes clients** et **1 500 à 2 000
commandes par jour**.

L'étude porte notamment sur : - la plateforme e-commerce et ses API ; -
les comptes clients, commandes et données personnelles ; - les identités
et les accès à l'environnement cloud ; - les prestataires externes,
notamment le paiement et la logistique ; - la disponibilité de la
plateforme et la capacité de restauration.

La démarche s'appuie principalement sur **EBIOS Risk Manager**, avec des
repères de gouvernance issus d'**ISO/IEC 27001:2022** et des thèmes de
protection des données du **RGPD**.

## Démarche suivie

Le travail suit une progression allant du cadrage à la préparation du
pilotage :

1.  **Cadrer** le périmètre, les objectifs et les limites de l'étude.
2.  **Cartographier** les valeurs métier, les biens supports et les
    besoins DICP.
3.  **Identifier et analyser** les événements redoutés, les sources de
    risque et les scénarios.
4.  **Évaluer et hiérarchiser** les risques selon leur vraisemblance et
    leur impact.
5.  **Proposer un traitement** avec des actions, des responsables, des
    échéances et des preuves attendues.
6.  **Définir la gouvernance** et les principaux sujets de conformité.
7.  **Construire un tableau de bord** avec des KPI/KRI et des seuils de
    suivi.
8.  **Présenter les résultats** dans une synthèse exécutive.
9.  **Documenter les sources et les preuves** nécessaires à la
    vérification des mesures.

## Livrables

  -----------------------------------------------------------------------
  Livrable                            Contenu
  ----------------------------------- -----------------------------------
  **L01 --- Note de cadrage**         Objectifs, périmètre, parties
                                      prenantes et limites

  **L02 --- Cartographie métier et    Valeurs métier, biens supports,
  SI**                                DICP et dépendances

  **L03 --- Dossier EBIOS RM**        Événements redoutés, écarts,
                                      sources de risque et scénarios

  **L04 --- Registre des risques**    Cotation, matrice et
                                      hiérarchisation des risques

  **L05 --- Plan de traitement**      Mesures proposées, responsables,
                                      délais et suivi

  **L06 --- Gouvernance et            Rôles, RACI, RGPD et
  conformité**                        correspondances ISO 27001

  **L07 --- Tableau de bord SSI**     KPI/KRI, cibles, seuils d'alerte et
                                      suivi

  **L08 --- Synthèse exécutive**      Résultats, priorités et arbitrage
                                      proposé

  **L09 --- Dossier de preuves**      Sources, hypothèses, entretiens
                                      simulés et preuves à collecter
  -----------------------------------------------------------------------

Les fichiers PDF et Excel sont disponibles dans ce dépôt. Les classeurs
Excel contiennent les tableaux de travail et les outils de suivi.

## Principaux risques étudiés

L'analyse fait ressortir cinq risques prioritaires dans le cas étudié :

-   **R-01 --- Compromission d'un compte administrateur cloud**
-   **R-02 --- Divulgation de données clients par export CSV**
-   **R-10 --- Protection insuffisante des comptes SaaS et des accès
    tiers**
-   **R-05 --- Indisponibilité majeure de la plateforme**
-   **R-04 --- Indisponibilité ou compromission d'un prestataire
    logistique**

La cotation utilise une échelle de vraisemblance et d'impact de 1 à 4.
La criticité est calculée par multiplication des deux notes. Les scores
sont des **évaluations de travail fondées sur le scénario**, et non des
résultats d'audit.

## Ce que ce projet met en pratique

-   Analyse des risques SSI et approche orientée métier
-   Méthode EBIOS Risk Manager
-   Cartographie des actifs et dépendances
-   Cotation et priorisation des risques
-   Élaboration d'un plan de traitement
-   Gouvernance SSI et matrice RACI
-   Sensibilisation aux exigences ISO/IEC 27001:2022 et RGPD
-   Définition de KPI/KRI et construction d'un tableau de bord
-   Préparation d'un arbitrage budgétaire et suivi des risques résiduels

## Périmètre et limites

ShopSecure est une organisation fictive créée pour cet exercice. Les
entretiens du L09 sont **simulés**. Les preuves techniques listées sont
des éléments à collecter dans un contexte réel ; elles ne sont pas
présentées comme ayant été obtenues.

Les mesures, responsables, échéances, seuils et arbitrages sont des
propositions à faire valider. Le projet ne revendique ni certification
ISO 27001 ni conformité RGPD démontrée.

## Structure du dépôt

``` text
.
├── README.md
├── Enonce_projet_GRC_Analyse_Risques_SSI_ShopSecure.pdf
├── L01_Note_de_cadrage_ShopSecure.pdf
├── L02_Cartographie_metier_et_SI_ShopSecure.pdf
├── L03_Dossier_EBIOS_RM_ShopSecure_Exercices_3_a_7.pdf
├── L04_Registre_des_risques.xlsx
├── L05_Plan_de_traitement_des_risques_ShopSecure.xlsx
├── L06_Gouvernance_et_conformite_ShopSecure.pdf
├── L07_Tableau_de_bord_SSI_ShopSecure.xlsx
├── L08_Synthese_executive_Analyse_des_risques_SSI.pdf
└── L09_Dossier_de_preuves_ShopSecure.pdf
```

*Les noms exacts des fichiers peuvent varier légèrement selon la version
déposée.*

## Sujet de l’exercice

Le sujet fourni dans le dépôt sert de référence pour les objectifs et les consignes du projet. Il est inclus pour faciliter la lecture des livrables et replacer l’analyse dans son contexte. Si ce document a été fourni par un établissement ou un tiers, vérifie que sa diffusion publique est autorisée avant de le publier sur GitHub.

## À propos

Projet personnel réalisé dans une démarche de mise en pratique des
compétences en **GRC et cybersécurité**.

Merci de consulter les livrables pour découvrir la démarche, les
analyses et les propositions détaillées.
