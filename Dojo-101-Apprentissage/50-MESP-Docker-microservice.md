# Déploiement d'un container Docker

Déploiement de code dans un microservice Docker

Durée: 8 jours

Ce contenu est publié sous licence "GNU GENERAL PUBLIC LICENSE Version 3" et les sources sont sur le projet Github Dojo-101, merci d'en tenir compte dans vos usages.


## Ressources

* [Gestes professionnels](https://github.com/Aif4thah/Dojo-101)
* [vulns-light-apps](https://github.com/Aif4thah/VulnerableLightApp)
* [Docker](https://www.docker.com/)
* [Exemple Kanban](https://www.jetbrains.com/fr-fr/youtrack/)
* [Docker Hub](https://hub.docker.com/)
* [Guide ANSSI](https://cyber.gouv.fr/publications/recommandations-de-securite-relatives-au-deploiement-de-conteneurs-docker)
* [Terraform](https://www.terraform.io/)



## Contexte

Vous faites partie de la purple team de l'entreprise. Afin de former les équipes du SOC à la détection des attaques, il vous est demandé de déployer vuln-light-apps dans un microservice docker.

Ce container sera ensuite utilisé par les équipes afin de mener leurs tests.

NB: *ce contexte est issu du Lab déjà mis en place*


## Modalités pédagogiques

1. Installer Docker

2. Vérifier que docker fonctionne (container Hello World)

3. Prendre connaissance du projet Vulnerable-light-App

4. Planifier dans un KanBan comment va se faire la mise en container de l'application.

    * Passer en revue les étapes suivantes et créer une liste de tâche (story).

    * Mettez un poids ou une difficulté (chiffre entier) sur chaque story.

    * Attribuez-vous les stories au sein du groupe.

    * Utiliser les colonnes "à venir", "en cours", "en test", "terminé" pour suivre l'avancement du Brief

5. Créer un docker file

6. Automatiser l'installation et le lancement de vuln-light-apps

7. Pousser votre travail sur un repo github.

8. Les tests de build doivent se faire automatiquement lors du push sur GitHub

9. Mettre à disposition votre container (Docker Hub / Registry)

10. Appliquer les bonnes pratiques de sécurité issues du Guide ANSSI 

11. Exporter les logs sur la machine hôte afin de garder les traces en cas de suppression de containers

12. Pour aller plus loin : réaliser un déploiement à l'aide de Terraform


## Modalités d'évaluation

* Test du container depuis une machine Linux

* Relecture des preuves de bonnes pratique de sécurité


## Livrables

 * un projet Github / Groupe, le repos doit contenir les Push/Merge/Pull Request de chaque utilisateur du groupe.

 * Identifiant de container / commande docker permettant de tester son fonctionnement.

 * Preuves de l'application des bonnes pratiques de sécurité et de la configuration des logs sur l'hôte


## Critères de performance

* La commande `docker run <container> -p 3000:3000` fonctionne.

* Les mesures de sécurité sont appliquées


## Pour finir


Si vous avez apprécié ce cours et souhaitez valoriser votre travail, n'hésitez pas à ajouter une ⭐ au [projet](https://github.com/Aif4thah/Dojo-101)

