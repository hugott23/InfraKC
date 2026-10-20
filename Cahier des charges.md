

## Mise en place du système d'information de la Karmine Corp

> C'est un projet étudiant. Ce document propose un système à partir d'informations publiques sur la structure. Il ne décrit pas le système réellement en place chez Karmine Corp et n'a aucun lien avec.

---

## 1. Contexte

Karmine Corp (KC) est une structure e-sport française fondée en 2020 par Kameto du zoo, dont le siège est à Paris. Elle aligne des équipes professionnelles sur League of Legends, Valorant et Rocket League.

La KC dispose de plusieurs secteur d'activité comme la compétition où elle a plusieurs équipes en championnats Français et mondiaux, la création de contenu pour la communauté, gestion de partenariat et de sponsoring et enfin la vente de produit dérivé comme des maillots etc...

La structure emploie une trentaine de personnes réparties entre la direction, l'administration, le service partenariats, le staff sportif, les joueurs, le pôle contenu et le service informatique. 

## 2 Besoin/Problématique

Les données de la structure sont dispersées entre les postes des salariés et des outils en ligne non officiel. Les statistiques des joueurs sont relevées manuellement et ne sont pas enregistré. L'audience générée par la structure n'est pas mesurée de façon consolidée alors qu'elle constitue son principal argument auprès des sponsors.

**Problématique :** Comment mettre en place un système d'information permettant à la Karmine Corp de centraliser ses données, d'exploiter les informations de performance de ses joueurs et d'assurer la disponibilité de ses services pendant les compétitions ?

## 3 Objectif

Mettre en place un système permettant de :

1. Centraliser les informations de la structure.
2. Automatiser la collecte et l'analyse de donnée.
3. Gérer les partenaires et contrats.
4. Présenter la structure au public et de mesurer son audience.
5. Protéger les données et d'assurer la disponibilité des services.

---

## 4. Utilisateurs

| Utilisateur              | Les besoins                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| Direction                | Suivre l'activité et accéder aux informations importantes          |
| Administration           | Gérer les documents administratifs                                 |
| Partenariats             | Gérer les sponsors, suivre les échanges                            |
| Staff sportif            | Analyser la performance des joueurs, préparer les prochains matchs |
| Joueurs                  | Consulter leurs statistiques                                       |
| Pôle contenu             | Stocker les contenus, alimenter le site Internet                   |
| Responsable informatique | Administrer et superviser le système                               |
| Public et partenaires    | Consulter les informations et contacter la structure               |

---

## 5. Données stockées

Le système d'information devra stocker les données suivantes :

| Donnée                                           | Caractère personnel | Conservation                   |
| ------------------------------------------------ | ------------------- | ------------------------------ |
| Comptes des salariés (nom, identifiant, service) | Oui                 | Durée du contrat               |
| Documents internes, contrats, contenus vidéo     | Partiellement       | 5 ans                          |
| Joueurs : pseudos, poste, tag ingame             | Oui                 | Durée du contrat               |
| Statistiques de parties collectées               | Oui                 | 2 ans                          |
| Partenaires, prospects et échanges commerciaux   | Oui                 | 3 ans après le dernier contact |
| Demandes et incidents informatiques              | Oui                 | 2 ans                          |
| Journaux système et de connexion                 | Oui                 | 1 an                           |
| Fréquentation du site Internet                   | Anonymisée          | 13 mois                        |

Le traitement de ces données devra respecter la réglementation : information des personnes concernées, durées de conservation définies, droit d'accès et de rectification, et accès restreint selon le profil de l'utilisateur.

---

## 6. Fonctionnalités

**Gestion des utilisateurs et des fichiers.** Créer et organiser les comptes par service, gérer les droits, authentifier les utilisateurs. Stocker et partager les documents de la structure, y compris les contenus vidéo.

**Suivi de la performance.** Récupérer automatiquement les données des parties jouées, consulter l'évolution des joueurs, comparer plusieurs joueurs et/ou périodes, enregistrer les entraînements, produire un rapport de synthèse. Chaque joueur accède à ses propres données, le staff à l'ensemble.

**Gestion du roster et des compétitions.** Identifier les joueurs et leur équipe, consulter le calendrier des matchs à venir et l'historique des résultats.

**Gestion des partenaires.** Gérer les sponsors et prospects, suivre les échanges et les opportunités, conserver l'historique et les documents contractuels.

**Site Internet.** Présenter la structure, ses équipes, ses joueurs et ses partenaires. Afficher le calendrier des matchs. Proposer un contenu interactif fidélisant les visiteurs. Permettre le contact. Mesurer la fréquentation.

**Support informatique.** Signaler un problème, suivre son état, ajouter des commentaires, intervenir sur les équipements informatique si un problème est rapporté par les joueurs.

**Administration et supervision.** Administrer les services, surveiller les serveurs, les équipements et la disponibilité, détecter les incidents, suivre l'utilisation des services.

---

## 7. Contraintes

**Infrastructure.** Adaptée pour les besoins actuels . Réseau isolant les services exposés sur Internet du réseau interne. Architecture documentée.

**Application de suivi de la performance.** Reposer sur une base de données. Récupérer automatiquement les données auprès d'une api externe. Restreindre l'accès selon le profil. Être accessible aux collaborateurs en déplacement.

**Site Internet.** Accessible depuis Internet, hébergé sans exposer le réseau interne. Respecter les conditions d'utilisation des ressources appartenant à l'éditeur du jeu. Permettre la mesure de fréquentation.

**Sécurité.** Contrôle des accès, sécurisation des comptes, des serveurs et des accès distants, filtrage. Des règles d'utilisation devront être définies.

**Données.** Protéger les données contre la perte, la modification et l'accès non autorisé, en particulier celles listées en section 5. Prévoir un contrôle des droits, une stratégie de sauvegarde, une procédure de restauration et des mesures de disponibilité.

**Sauvegarde.** Sauvegardes régulières et conservées.

**Supervision.** Surveiller les serveurs, les services, les équipements réseau et la disponibilité. Suivre l'utilisation des services.

**Documentation.** Documenter l'architecture, les équipements, les services, les droits, la sécurité, la sauvegarde et les procédures de reprise. Produire des supports destinés aux utilisateurs.