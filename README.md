# Configuration pour Overextended

- Description : Fichier overextended.cfg contenant la configuration pour ox_inventory et ox_target.


ensure oxmysql
ensure es_extended
ensure [2-esx-core]

## ESX OVEREXTENTED
ensure ox_lib
ensure ox_target
ensure [overextended]



# Installation


> [!IMPORTANT]
> Envoyez le fichier overextended.cfg sur votre hébergeur, au même emplacement que votre server.cfg

> [!IMPORTANT]
> Ajoutez la ligne suivante à la fin de votre server.cfg : **exec overextended.cfg**

> [!NOTE]
> Télécharger config overextended : 

> [!NOTE]
> Télécharger ox_lib : https://github.com/overextended/ox_lib/releases

> [!NOTE]
> Télécharger ox_inventory : https://github.com/overextended/ox_inventory/releases

> [!NOTE]
> Télécharger ox_target : https://github.com/overextended/ox_target/releases

> [!NOTE]
> Télécharger ox_fuel : https://github.com/overextended/ox_fuel/releases

> [!NOTE]
> Télécharger ox_doorlock : https://github.com/overextended/ox_doorlock/releases

> [!IMPORTANT]
> Créez un nouveau dossier nommé **[overextended]** dans votre dossier resources. 

> [!NOTE]
> Démarrez les ressources dans cet ordre :
> ensure oxmysql
> ensure es_extended
> ensure [core]
> ensure ox_lib
> ensure ox_target
> ensure [overextended]
