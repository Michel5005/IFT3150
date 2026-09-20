---
title: Vue d'ensemble du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Vue d'ensemble du projet

!!! info "Informations générales"
    **Session**: Automne 2026  
    **Auteur(s)**: Michel Vuu (20278607)  
    **Thème(s)**: Développement web  
    **Superviseur(s)**: Louis Edouard Lafontant 
    **Collaborateur(s):** Massimo Costarella-Serra

## Description du projet

> :bulb: N'oubliez pas d'effacer ou mettre en commentaires les notes (`>`) en début de section

### Contexte

La Fédération des astronomes amateurs du Québec (FAAQ) regroupe 26 clubs et environ 2000 membres au Québec. Afin de gérer ses adhésions, ses paiements, ses communications et l'accès à ces services, elle utilise présentement des méthodes obsolètes, qui rend la maintenance difficile. La conception d'un backend Spring Boot a déjà été commencée par la FAAQ. Cependant, le frontend reste complètement à concevoir et à développer. Ce projet s'inscrit dans un chantier réel et actif, où l'équipe contribuera au backend et au frontend.

### Problématique

La FAAQ compte 26 clubs membres, environ 2000 membres et plus de 1200 transactions annuelles. Présentement, elle utilise un système d'adhésion, WordPress avec des plugins, MailChimp et ARMember. Ces outils sont peu intégrés, dispersés et les mises à jour doivent être fait manuellement. Ceci entraîne des coûts élevés, des données qui se repètent, un service à la clientèle insuffisant ainsi qu'une gestion complexe. La FAAQ cherche donc une plateforme qui regrouperait la gestion des membres, des communications, des paiements, des inscriptions et des accès. Ceci permettrait de réduire les coûts, améliorer l'efficacité ainsi qu'offrir une experience meilleure et moderne aux utilisateurs

### Proposition et objectifs

Nous allons poursuivre le développement de la plateforme de gestion des membres de la FAAQ, en développant le frontend. De mon bord, je m'occuperais plus spécifiquement du côté admin, donc tout ce qui est question de gestion de privilèges, des clubs.

Objectifs

1. Comprendre l'architecture microservices Spring Boot déjà envisagée par la FAAQ
2. Consolider et poursuivre le développement de certaines composantes
3. Concevoir et développer le frontend de la plateforme
4. Relier les interfaces aux services backend
5. Documenter les choix de conception et les décisions techniques
6. Produire un prototype fonctionnel exploitable qui couvre la gestion des membres, des familles, des clubs, des abonnements et des privilèges d'accès et des paiments/reçus
7. (Bonus) Intégration avec le site WordPress actuel de la FAAQ


### Méthodologie

Sachant que le protoypage a déjà été conçue, la méthodologie qui sera utilisé est le suivant:

1. Analyse : Étudiez le backend Spring Boot existant, et analyse des demandes de la FAAQ
2. Développement avec le modèle Sprint : Développer de manière itérative rapides le backend et frontend, avec démonstration au superviseur et feedback à la fin d'une itération
3. Intégration continue : Envoie le code à la branche principale quand une tâche a été complétée
4. Documentation : Prendre en notes chaque décision prise tout au long du projet

### Validation et Évaluation

- Scénarios principales : Visitez chaque action possible (Inscription d'un membre, gestion de club, etc)
- Tests : Tests unitaires et d'intégration sur les interfaces ainsi que sur le backend
- Feedback utilisateurs : Rétroaction sur les prototypes présentées à chaque itérations par membres de la FAAQ

## Échéancier (À voir)

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités                      | Début   |   Fin   | Livrable                            | Statut      |
|--------------------------------|---------|---------|-------------------------------------|-------------|
| Ouverture de projet            | 4 mai   | 15 mai  | Proposition de projet               | ✅ Terminé  |
| Études préliminaires           | 4 mai   | 22 mai  | Document d'analyse                  | 🔄 En cours |
| Présentation + Rapport         | 7 aout  | 14 aout | Présentation + Rapport              | ⏳ À venir  |
