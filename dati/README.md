# Dati

This folder contains:

* a QGIS project file (segnali_stradali.qgs)
* a GeoPackage file (dati_segnali.gpkg) in which are stored:
  * a point vector layer (t_grupposegnale)
  * a table (r_segnale_fisico)
  * several tables (named grupposegnale_\*)
  * several tables (named segnalefisico_\*)
  
The vector layer **t_grupposegnale** is the layer in which the points taken in the field must be saved (both geometry and related information). It represents the object (structure, pole, etc.) on which one or more road signals can be attached.
The table **r_segnale_fisico** is the table in which the information related to each road sign attached on the structure (t_grupposegnale) must be saved. The layer **t_grupposegnale** and the table **r_segnale_fisico** must be joined through a relation (1 --> n).

The tables (grupposegnale_\* and segnalefisico_\*) contains the codes and their descriptions that the different fields of  **t_grupposegnale** and **r_segnale_fisico** can have. These tables have to be used to define a value map widget for the field they refer to in t_grupposegnale and r_segnale_fisico. In the case of tables with codes like 0 1 (description: no yes) or similar, it is better to define a checkbox widget. In the case of fields which should store data/time information, it is better to use a Data/Time widget and so on.

To do:
------

* create the relation between **t_grupposegnale** and **r_segnale_fisico**
* create the form for alphanumeric data entry choosing the proper layout, widgets, filed aliases, etc.
* manage and organize data depending on the requirements of each App
