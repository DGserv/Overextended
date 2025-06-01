# Configuration pour Overextended

- Description : Fichier overextended.cfg contenant la configuration pour ox_inventory et ox_target.


# Téléchargement

Télécharger ox_lib
```
https://github.com/overextended/ox_lib/releases
```

Télécharger ox_inventory
```
https://github.com/overextended/ox_inventory/releases
```

Télécharger ox_target
```
https://github.com/overextended/ox_target/releases
```

Télécharger ox_fuel
```
https://github.com/overextended/ox_fuel/releases
```

Télécharger ox_doorlock
```
https://github.com/overextended/ox_doorlock/releases
```

# Installation


> [!NOTE]
> - Envoyez le fichier overextended.cfg sur votre hébergeur, au même emplacement que votre server.cfg
> - Ajoutez la ligne suivante à la fin de votre server.cfg : **exec overextended.cfg**
> - Créez un nouveau dossier nommé **[overextended]** dans votre dossier resources. 
> - Démarrez les ressources dans cet ordre :

- ensure oxmysql 
- ensure es_extended 
- ensure [core] 
- ensure ox_lib 
- ensure ox_target 
- ensure [overextended]
