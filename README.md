# ANSIBLE

### **Ansible** est une plateforme open-source de gestion de configuration et d'automatisation des déploiements. <br>L'objectif principal d'Ansible est de simplifier les tâches d'automatisation et d'orchestration des opérations informatiques. <br> Il permet de décrire l'état souhaité de l'infrastructure dans des fichiers appelés "playbooks", écrits en utilisant le langage **YAML**. <br> Les playbooks contiennent des instructions déclaratives qui spécifient les tâches à effectuer, telles que la configuration des serveurs, le déploiement d'applications, la gestion des paquets logiciels, la création de machines virtuelles, etc.

<br>

# INSTALLATION NÉCESSAIRE

### ! L'utilisation de la commande "sudo" (superuser do) est nécessaire dans certaines situations lorsque vous souhaitez exécuter des commandes en tant qu'utilisateur root ou superutilisateur. <br> Il est important de noter que l'utilisation de "sudo" doit être effectuée avec prudence, car elle vous donne des privilèges administratifs qui peuvent potentiellement causer des dommages au système si vous exécutez des commandes incorrectes ou malveillantes. <br>

<br>

_Avant toute chose Linux et ses packages doit-être à jour_ : <br>
**sudo apt update** <br>
**sudo apt upgrade**
<br>
**YAML** est destiné à prendre en charge la configuration d'un serveur sur un hôte donné. Pour cela nous utiliserons **apache2** (serveur) : <br>
**sudo apt install apache2**
<br>
_Puis installé ansible_ : <br>
**sudo apt install ansible**
