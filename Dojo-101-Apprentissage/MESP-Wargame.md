# War Game (exercice final)

Vous êtes chargé de défendre votre VM et d'attaquer celles des autres groupes

Durée: 2 jours 

Ce contenu est publié sous licence "GNU GENERAL PUBLIC LICENSE Version 3" et les sources sont sur le projet Github Dojo-101, merci d'en tenir compte dans vos usages.

## Ressources

* [Target Of Evaluation](https://github.com/Aif4thah/VulnerableLightApp)

* [Gestes professionnels](https://github.com/Aif4thah/Dojo-101)


## Contexte

Vous êtes des experts en sécurité informatique, engagés pour défendre une infrastructure sensible. 
Votre mission est de défendre votre VM tout en lançant des attaques sur celles de vos adversaires. 


## Modalités pédagogiques

Binôme ou seul (au choix)

les délais exacts seront déterminés selon le Lab et les participants

* T0 : installer une VM Windows serveur dans un hyperviseur à jour, lui-même sur une machine physique de test, vierge de toutes données et à jour.

* T1 : télécharger l'application vulnérable et exposez la sur le réseau du Lab. Elle doit être accessible aux autres groupes, vous avez le droit de choisir les ports TCP entre 80 et 1100.

* T2 : sans modifier l'application, configurer l'OS pour être en mesure de détecter les attaques. Vous pouvez configurer les Logs, la stratégie d'audit, utiliser un IDS, un SIEM.

* T3 : Communiquer votre IP, vos cibles (et la surface d'attaque) seront les IP adverses.

* T4 : Hackez les machines adverses, tout en détectant les intrusions sur votre Machine. 

* T5 : Arrêt des machines et décompte des points

* T6 : Retour à T0 ou Effacement sécurisé des serveurs, vérification que le niveau de sécurité n'a pas été détérioré.

**Important : Interdiction d'attaquer d'autres IP que celles transmises par les adversaires. Les hyperviseurs, les machines physiques, ainsi que les équipements réseau doivent rester intègres.**


## Modalités d'évaluation

**Chaque vulnérabilité ne peut être exploitée qu'une seule fois sur chaque VM**

* Chaque connexion TCP/UDP `victime -> attaquant` déclenchée par un exploit rapporte **1 point**
* Chaque création de fichiers pourtant le nom de l'attaquant sur la machine de la victime rapporte **2 points**
* Chaque détection d'intrusion rapporte **1 point**



## Livrables

Rapport PDF avec

* Le nombre de points revendiqué

* Captures d'écran des traces des incidents de sécurité sur votre machine

* Captures d'écran prouvant les exploitations réussies sur les machines adverses



## Critères de performance

Score final

## Pour finir

Si vous avez apprécié ce cours et souhaitez valoriser votre travail, n'hésitez pas à ajouter une ⭐ au [projet](https://github.com/Aif4thah/Dojo-101)