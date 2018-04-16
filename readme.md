Prérequis

Avant toute chose, l'installation de ces logiciel 
est névéssaire pour que le module fonctionne:

sudo apt-get install etherwake
sudo npm i wake-on-lan

(si l'installtion ne fonctionne pas :sudo apt-get update && sudo apt-get upgrade)

Installation

1/Installer le module dans gladys

Utilisation

Pour éveiller un ordinateur une fois la configuration
terminée, il suffis d'executer le script suivant dans gladys:

gladys.modules.wol.wakeonlan()


