## 1. Contexte & Problématique

- **Organisation :** Karmine Corp (cas pratique/projet étudiant). Structure e-sport (LoL, Valorant, Rocket League) comptant une trentaine de collaborateurs.
    
- **Situation actuelle :** Données dispersées (fichiers locaux, outils non officiels), relevés de statistiques manuels, mesure d'audience non consolidée.
    
- **Objectif central :** Déployer un Système d'Information (SI) centralisé, sécurisé et hautement disponible pour piloter l'activité sportive, commerciale et administrative.
    

## 2. Utilisateurs & Besoins

|**Profil**|**Besoin Principal**|
|---|---|
|**Direction & Administration**|Pilotage global, gestion documentaire, suivi administratif.|
|**Staff & Joueurs**|Suivi du calendrier, analyse automatique des statistiques de jeu (individuelles et d'équipe).|
|**Pôle Partenariats**|Gestion de la relation client (CRM) : sponsors, prospection, contrats.|
|**Pôle Contenu**|Stockage centralisé (notamment vidéos) et gestion du site web.|
|**Service Informatique**|Support technique (ticketing), supervision et administration de l'infrastructure.|
|**Public & Sponsors**|Portail d'information vitrine, suivi des plannings, formulaire de contact.|

## 3. Périmètre Fonctionnel

- **Identité & Fichiers :** Annuaire centralisé avec gestion fine des droits d'accès. Stockage partagé pour les documents internes et fichiers lourds (vidéos).
    
- **Portail Sportif :** Application connectée à des API externes pour automatiser la remontée des statistiques de jeu. Tableaux de bord de performance avec accès segmentés (vue globale pour le staff, vue individuelle pour le joueur).
    
- **Gestion Commerciale :** Suivi de l'historique des échanges partenaires et centralisation des documents contractuels.
    
- **Présence Web :** Site internet vitrine interactif intégrant le calendrier des matchs, les rosters et des outils de mesure d'audience.
    
- **Support IT :** Plateforme de déclaration et de suivi des incidents (ticketing) et tableau de bord de supervision réseau/serveurs.
    

## 4. Gestion des Données & Conformité

- **Type de données :** RH (comptes, contrats), Sportives (pseudos, statistiques), Commerciales (prospects, partenaires), Techniques (logs, tickets d'incidents, analytics web).
    
- **Règles de gouvernance (RGPD) :**
    
    - Durées de conservation strictes (ex: 13 mois pour l'audience web, 1 an pour les logs, 5 ans pour l'administratif).
        
    - Anonymisation systématique de la fréquentation du site internet.
        
    - Restriction d'accès basée sur les rôles professionnels.
        

## 5. Contraintes Techniques & Sécurité

- **Architecture Réseau :** Ségrégation stricte (cloisonnement) entre le réseau interne de la structure et la zone exposée à Internet (hébergement du site web).
    
- **Accessibilité :** Applications métiers disponibles à distance et de manière sécurisée pour les collaborateurs en déplacement.
    
- **Sécurité & Résilience :** Politique de contrôle d'accès, sécurisation des serveurs, filtrage réseau. Mise en place de sauvegardes régulières testées et d'un plan de reprise d'activité.
    
- **Documentation :** Fourniture obligatoire d'une documentation technique complète (architecture, sécurité, sauvegardes) et de guides utilisateurs.