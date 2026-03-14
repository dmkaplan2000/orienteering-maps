# Orienteering maps / Cartes de courses d'orientation

## Français

Ce dépôt contient une série de cartes de courses d'orientation publiées sous licence Creative Commons,
ce qui signifie qu'elles peuvent être utilisées et
modifiées à votre guise.

Les cartes ont été créées avec [Open Orienteering Mapper](https://www.openorienteering.org/apps/mapper/) et les parcours d'orientation ont été conçus avec [Purple Pen](https://www.purple-pen.org/). Chaque carte se trouve dans son propre
répertoire. Outre les cartes elles-mêmes, les données sources pour
leur création (par exemple, données de terrain et d'altitude LiDAR, OpenStreetMap et données d'imagerie satellite ESRI) ont été téléchargés et traités avec [R](https://posit.co/download/rstudio-desktop/).
Les détails de ce traitement de données sources sont fournis dans les scripts `download-templates.qmd` de chaque répertoire de carte. Ce script est assez générique et peut être
modifié pour créer d'autres cartes (bien que certaines données sources puissent être
uniquement accessibles au public en France).

## English

This repository contains a series of orienteering maps released under
the Creative Commons license meaning that they can be used and
modified as you wish.

Maps have been created using [Open Orienteering Mapper](https://www.openorienteering.org/apps/mapper/) and any
orienteering courses were created with [Purple
Pen](https://www.purple-pen.org/). Each map is in its own
directory. In addition to the maps themselves, template files for
creating maps (e.g., LIDaR terrain and height data, OpenStreetMap and
ESRI satellite imagery data) were downloaded and processed using [R](https://posit.co/download/rstudio-desktop/), the
details of which are provided in the `download-templates.qmd` scripts
in each map directory. This script is fairly generic and may be
modified for making other maps (though some of the source data may be
only publicly available in France).

# Map status / État des cartes

## Français

|Carte|Nom du répertoire|Coordonnées de la zone (Long,Lat)|Statut|
|---|--------------|---------------------|------|
|Puit de Laven|`puit-de-laven`|[3.705485,43.58077](https://www.openstreetmap.org/#map=16/43.58077/3.705485)|Carte OOM et fichiers Purple Pen terminés, mais perfectibles|
|Domaine de Mas Nau|`domaine-mas-nau`|[3.854343,43.84696](https://www.openstreetmap.org/#map=16/43.84696/3.854343)|Uniquement le script de téléchargement des modèles est disponible pour le moment|

## English

|Map|Directory name|Zone coord. (Lon,Lat)|Status|
|---|--------------|---------------------|------|
|Puit de Laven|`puit-de-laven`|[3.705485,43.58077](https://www.openstreetmap.org/#map=16/43.58077/3.705485)|OOM map and purple pen files finished, but can be improved|
|Domaine de Mas Nau|`domaine-mas-nau`|[3.854343,43.84696](https://www.openstreetmap.org/#map=16/43.84696/3.854343)|Only templates download script done for now|
