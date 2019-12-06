Ce document vous permettra de configurer plus facilement votre application mobile **[HomeControl](https://play.google.com/store/apps/details?id=fr.touin.thierry.homecontrol&hl=fr)**.

## Configuration backoffice
Vous devez aller sur les pages de configuration en cliquant sur le bouton ![roueDents](./images/roueDents.png)

Vous arrivez sur une page avec 4 onglets

1. L'onglet **Jeedom** vous permettra de configurer l'accès à votre box Jeedom

Le lien vers votre box peux ressembler a ça
```
 http://#IP_JEEDOM#/core/api/jeeApi.php?apikey=#APIKEY
```
Cette page est partagée en 4 zones. En réalité, elle vous permet de renseigner le lien vers votre box Jeedom.
- Le **Protocol** est **http** ou **https** suivant votre installation.
- Le **Domain** correspond à l'adresse IP ou le nom de domaine de votre box.
- Le **Port** est en général 80 (http) ou 443 (https). Dans tous les cas, vous devez renseigner la valeur.
- La **Clé Jeedom** est la clé d'API de votre box. Vous devez la récuperer via l'interface Web de cette dernière. 


2. L'onglet **Pages** vous permettra de nommer les onglets principaux. 
Attention un redémarrage de l'application est necessaire pour prise en compte.

3. L'onglet **IMP/EXP** vous permettra d'importer et d'exporter la configuration. Par exemple si vous changez de téléphone. 
La sauvegarde **HomeControlConfig.json** est localisée dans le répertoire **[sdcard]/HomeControl** de votre téléphone. Elle est au format **json**. 

4. L'onglet **Debug** vous permet d'activer un mode facilitant l'analyse si vous détectez un problème dans l'application. Cet onglet est réservé au expert.



## Configuration des widjets

