# Versions ezPAARSE #

## 2.3.0  ## 
##### 09/04/2015 - MVP Open Access #####
- Gestion de l'exclusion des adresses IP des robots
- Nouvel outil d'aide à la détermination du format de log
- Dédoublonnage inter-format
- mémorisation des prédéfinis dans les instances locales

## 2.2.0  ## 
##### 05/02/2015 - Gestion des PKB de gros volumes #####
- optimisation de la gestion NoSQL des PKB via castor-js
- amélioration des temps d'initialisation de l'application
- Améliorations ergonomiques du formulaire (nom de fichiers, headers avancés, messages d'alerte)

## 2.1.0  ## 
##### 31/10/2014 - NoSQL embarqué #####
- Mise à jour de semantic-UI
- NoSQL embarqué dans la branche castor
- Ajout des génériques dans les pré-definis
- Ajout de nouveaux parseurs (juridique)
- Fichier des domaines inconnus téléchargeable

## 2.0.0  ## 
##### 01/09/2014 - Administration des PKB #####
- Interface de visualisation des PKB
- Mise à jour via l'interface des PKB
- Mise à jour via l'interface du logiciel
- Outil de dédoublonnage des PKB
- MVP de la page mon profil
- ajout du publisher_name dans les EC

## 1.9.0  ## 
##### 23/06/2014 - Parsathon #####
- Reconnaissance de 50 plateformes
- Debut de travail Open Access

## 1.8.0  ## 
##### 13/03/2014 - MVP des alertes sur anomalies #####
- Notification de fin de traitement
- Alerte sur domaine inconnu dans le traitement

## 1.7.0  ## 
##### 13/03/2014 - Validation de l'interface Web #####
- Validation de l'interface Web
- Refactoring platform-plugin

## 1.6.0  ## 
##### 13/03/2014 - Refonte de l'interface Web #####
- Refonte de l'interface Web avec AngularJS
- Geolocalisation des ECs

## 1.5.0  ## 
##### 03/02/2014 - Normalisation KBART #####
- normalisation KBART des PKB
- version Libre Office de la macro de rendu

## 1.4.0  ## 
##### 30/01/2014 - Export COUNTER #####
- export COUNTER JR1
- gestion des informations de non-usage

## 1.3.0  ## 
##### 19/12/2013 - Multilinguisme #####
- multilinguisme (interface, version windows)
- MVP export COUNTER

## 1.2.0  ## 
##### 14/11/2013 - Sécurisation #####
- sécurisation des accès aux pages (possiblité de protection par mot de passe)

## 1.1.0  ## 
##### 10/10/2013 - Produit Minimum Viable de synchronisation des Platform Knowledge Bases #####
- réorganisation des modules de dépôt
- apport des scrapers (génération automatique de PKB)
- gestion de la synchronisation automatique des PKB

## 1.0.0  ## 
##### 09/09/2013 - Version 1 #####
- amélioration du package windows : objectif de démonstration d'usage du fichier de log jusqu'au rendu tableur
- correction de bug lié au navigateur

## 0.9.0  ## 
##### 08/08/2013 - Dédoublonnage COUNTER des événements de consultation - candidate version 1 #####
- automatisation pkb/outil ezPAARSE
- amélioration de la qualité du code
- dédoublonnage COUNTER des événements de consultation

## 0.8.0  ## 
##### 27/06/2013 - Produit Minimum Viable des User Knowledge Base #####
- gestion des User-Fields
- gestion des options avancées/valeurs pré-définies dans le formulaire
- traduction des requêtes produites par le formulaire en cURL en vue d'automatisation des traitements
- ajout de traces, corrections de bug

## 0.7.0  ## 
##### 05/06/2013 - Consolidation du coeur #####
- meilleure caractérisation des EC (rtype, MIME, unitid)
- test de gros volume
- ajout de nouveaux parseurs (BMC, lamyline, lextenso, lexisnexis)
- refonte du formulaire avec métriques dynamiques
- accès aux traces et aux fichiers des lignes filtrées (formats non reconnus, domaines non reconnus, ...)

## 0.6.0  ## 
##### 18/04/2013 - Consolidation des reconnaissances de plateforme #####
- Passage en node V 0.10
- ajout de nouveaux parseurs (dalloz, wiley)
- ajout de nouvelles traces

## 0.5.0  ## 
##### 27/03/2013 - Utilisabilité d'ezPAARSE #####
- Mise à disposition d'un installeur Windows
- Mise en place d'un formulaire d'envoi des log

## 0.4.0  ## 
##### 21/02/2013 - Extension des cas d'usage #####
Extension de la reconnaissance des formats de log des fichiers de journalisations des serveurs mandataires (de type EZproxy, Bibliopam, Squid)

## 0.3.0  ## 
##### 31/01/2013 - Extension du domaine des parseurs #####

- Documentation précise de comment faire pour reconnaître des EC
- Développement de nouveaux parseurs pour différents types de plateformes
  - sd (Science Direct) : parseur pour plateforme sans base de connaissance, un identifiant normalisé est disponible dans l'URL
  - npg (Nature Publishing Group) : parseur pour plateforme avec base de connaissance, un identifiant interne est utilisé
  - edp (EDP Sciences) : parseur pour plateforme mono-revue (une plateforme correspond à une revue, mais les plateformes utilisent le même logiciel de mise en ligne)

## 0.2.0  ## 
##### 20/12/2012 - Installation générique #####
Installation du MVP produit au sprint 1 dans des environnements multiples (OS différents : Ubuntu, fedora, RedHat, Suse)

## 0.1.0  ## 
##### 06/12/2012 - Minimum Viable Product #####
Production d'événements de consultations (EC) à partir de fichiers de log pour la plateforme Science Direct via un web service RESTful

