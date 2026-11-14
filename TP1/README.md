ETAPE 1:



&#x09;1. Expliquez, avec vos propres mots, ce qu’est une machine virtuelle.



Une machine virtuelle est une représentation logicielle d'une machine. Celle ci se trouve dans une machine physique. Elle a ses propres ressources matérielles virtuelles ce qui lui permet donc d'exécuter ses propres applications et son propre OS.



&#x09;2. Citez deux avantages de la virtualisation dans un environnement professionnel.



Deux avantages de la virtualisation dans un environnement professionnel sont :

* la possibilité d'isoler ses applications et environnement tout en travaillant avec la même machine
* Une optimisation des ressources (meilleure utilisation des ressources matérielles ce qui peut conduire à une moindre consommation d'énergie)


&#x09;3. Quelle différence existe-t-il entre travailler directement sur votre ordinateur et travailler dans

une machine virtuelle?

La principale différence entre une machine virtuelle et une machine physique est que la machine physique a un OS qui utilise directement les ressources matérielles tandis que la machine virtuelle a un OS qui utilise des ressources virtualisées par un hyperviseur.

Les machines virtuelles offrent également une plus grande flexibilité. Il est possible de créer, supprimer ou modifier les machines virtuelles sans affecter directement le système hôte. De même, il est possible de conserver un état particulier des machines virtuelles à l'aide de snapshot. Ceci facilite notamment les tests et expérimentations.


ETAPE 2:



&#x09;1. Expliquez, avec vos propres mots, ce qu’est un conteneur Docker.



Un conteneur Docker est un environnement d'exécution isolé (les processus d'un conteneur ne peuvent pas voir les processus d'un autre ) utilisant le même OS



&#x09;2. Quelle différence fondamentale existe entre une machine virtuelle et un conteneur?



Une machine virtuelle a son propre OS alors que le conteneur non.



&#x09;3. Pourquoi les conteneurs sont-ils particulièrement adaptés au déploiement d’applications dans

le Cloud



Les conteneurs sont particulièrement adaptés au déploiement d'applications dans le Cloud car il permettent la reproductibilité et la portabilité. Or, dans le Cloud les principaux avantages sont l'accessibilité quelque soit notre appareil ainsi que la flexibilité.



ETAPE 3:



&#x09;1. Pourquoi un Dockerfile est-il préférable à la configuration manuelle d’un conteneur?



C'est plus facile à reproduire à grande échelle, donc gain de temps et moins de chance de faire des erreurs.



&#x09;2. Quelle différence existe entre une image Docker et un conteneur Docker?



La différence entre une image et un conteneur Docker c'est leur nature. Une image Docker est un modèle reproductible de l'environnement tandis qu'un conteneur est une application en exécution. 



EPATE 4:



&#x09;1. Pourquoi Docker Compose est-il préférable au lancement manuel de plusieurs conteneurs?



Docker Compose est préférable au lancement manuel de plusieurs conteneurs car il permet d'orchestrer le lancement des conteneurs. Cela facilite le travail (temps, grande échelle).



&#x09;2. Quel est le rôle du fichier "docker-compose.yml"?



Le fichier docker-compose.yml est le descriptif qui permet à Docker Compose d'orchestrer le lancement des conteneurs.



&#x09;3. Dans quels cas Docker Compose pourrait-il montrer ses limites?



Docker Compose pourrait montrer ses limites si un service tombe en panne ou alors si on utilise plusieurs machines différentes.

