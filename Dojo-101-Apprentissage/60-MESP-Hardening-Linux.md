# Hardening / Durcissement Linux

Vous êtes chargé de renforcer le niveau de sécurité de l'infrastructure.

Durée estimée: 3 jours

Ce contenu est publié sous licence "GNU GENERAL PUBLIC LICENSE Version 3" et les sources sont sur le projet Github Dojo-101, merci d'en tenir compte dans vos usages.

## Ressources

* [Guides ANSSI](https://cyber.gouv.fr/publications)
* [Gestes professionnels](https://github.com/Aif4thah/Dojo-101)
* [Ansible](https://www.ansible.com/)
* [Ansible Quick Start](https://docs.ansible.com/ansible/latest/getting_started/index.html)
* [Chaine DevOps](https://learn.microsoft.com/fr-fr/azure/cloud-adoption-framework/ready/considerations/devops-toolchain#azure-devops-and-github-toolchain)


## Contexte

Vous êtes un auditeur de sécurité pour une entreprise de développement de logiciels. L’entreprise utilise une infrastructure Windows Active Directory (AD) pour gérer les identités et les accès des utilisateurs. L’infrastructure AD est composée d'un seul controleur de domaine et d’un serveur Linux non intégré au domaine. L’entreprise a également développé une API REST personnalisée qui est utilisée par plusieurs applications internes. Votre tâche consiste à auditer la sécurité de l’infrastructure AD, du serveur Linux et de l’API REST pour identifier les vulnérabilités et les risques potentiels.

Votre tâche consiste à appliquer les bonnes pratiques de sécurité suite à l'audit (MESP Audit), soit manuellement, soit par script, soit à l'aide d'une solution de type Infrastructure as Code (IaC).

NB: *ce contexte est issu du Lab déjà mis en place*

## Modalités pédagogiques

Binôme ou seul (au choix)


## Modalités d'évaluation

Relecture par le formateur de la procédure de durcissement


## Livrables

* procédure de durcissement (sans Ansible)
* PlayBook (+rôle) Ansible ou (fichier PowershellDSC) poussé sur Github (meme si il a été localement)


## Critères de performance

* Procédure claire, concise et d'un bon niveau technique
* Le rôle (ou équivalent) corrige les vulns trouvées lors de l'audit (MESP-audit-conf*)
* La solution tourne dans le Lab et l'enrichit (MESP-création-Lab)
* Le niveau de sécurité n'est pas dégradé du fait des scripts ou de la solution IaC


## Pour finir

Si vous avez apprécié ce cours et souhaitez valoriser votre travail, n'hésitez pas à ajouter une ⭐ au [projet](https://github.com/Aif4thah/Dojo-101)