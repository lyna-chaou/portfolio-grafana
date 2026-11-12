# portfolio-grafana
# Exploitation et visualisation de données — PostgreSQL & Grafana

Ce dossier portfolio a été réalisé en première année de BUT Informatique dans le cadre du module d'exploitation des bases de données (R2.06). L'objectif était de mettre en pratique l'administration, l'interrogation SQL et la visualisation de données à partir de la base `brigade_criminelle` sous environnement Linux.

Après avoir restauré la base sous PostgreSQL et géré les droits d'accès via les rôles, j'ai rédigé plusieurs requêtes d'analyse (jointures, agrégations, sous-requêtes) ainsi qu'une vue SQL (`vue_synthese_affaires`) pour simplifier le suivi des dossiers par type et par statut. Ces requêtes ont ensuite été reliées à Grafana afin de construire un tableau de bord interactif regroupant des indicateurs clés, un graphique en barres, une courbe d'évolution mensuelle, un tableau des dossiers anciens et une carte géographique par département. Le dépôt contient le portfolio complet détaillant l'architecture, le modèle relationnel et les sauvegardes (`pg_dump`), ainsi que l'export du dashboard.
