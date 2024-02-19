# Databricks-Accident-Project

Nous avons récupéré des données du site data.gouv.fr.

Il y a 4 fichiers :
carac.csv nous donne des caractéristiques sur les accidents
lieux.csv recense des données sur les lieux des accidents
veh.csv donne des informations sur les véhicules impliqués
vict.csv donne des informations sur les victimes

A partir de ces données, nous voulons prédire la classe "gravité" dans la table victime, qui désigne la gravité de l'accident.
En effet toutes les victimes sont listées et notées selon leur gravité de dégats : indemne, tué, hospitalisé et blessé léger.
A partir de tous les autres paramètres que nous avons à notre disposition, nous voulons prédire cette dernière variable gravité de l'accident. 

Nous pouvons voir dans mon repo que nous avons un notebook en python qui établis toute la démarche de prédiction de variable. J'ai essayé plusieurs méthodes différentes. 
