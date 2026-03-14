# Orienteering maps

This repository contains a series of orienteering maps released under
the Creative Commons license meaning that they can be used and
modified as you wish.

Maps have been created using [Open Orienteering Mapper](https://www.openorienteering.org/apps/mapper/) and any
orienteering courses were created with [Purple
pen](https://www.purple-pen.org/). Each map is in its own
directory. In addition to the maps themselves, template files for
creating maps (e.g., LIDaR terrain and height data, OpenStreetMap and
ESRI satellite imagery data) were download and processed using R, the
details of which are provided in the `download-templates.qmd` scripts
in each map directory. This script is fairly generic and may be
modified for making other maps (though some of the source data may be
only publicly available in France).

# Map status

|Map|Directory name|Zone coord. (Lon,Lat)|Status|
|---|--------------|---------------------|------|
|Puit de Laven|`puit-de-laven`|[3.705485,43.58077](https://www.openstreetmap.org/#map=16/43.58077/3.705485)|OOM map and purple pen files finished, but can be improved|
|Domaine de Mas Nau|`domaine-mas-nau`|[3.854343,43.84696](https://www.openstreetmap.org/#map=16/43.84696/3.854343)|Only templates download script done for now|
