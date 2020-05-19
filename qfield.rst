.. image:: img/qfield-logo.png

QField
==================================

Un mobile GIS app con gli obiettivi di accedere ai QGIS strumenti necessari sul terrano.


.. note:: L'analisi dell'applicazione è realizzato sulla versione 1.5.3 - Piz Palü di QField.


Installazione
----------------------------------

QField è un app per Android sistemi. 
L'ultima versione è disponibile a questo `link <https://github.com/opengisch/QField/releases/>`__ o su Google Play.

L'app usa un progetto QGIS esistente. Per vedere ed modificare dati, bisogna di:

#. Creare il progetto su QGIS Desktop
#. Creare o aggiungere i layers, le style, etc...
#. Esportare il progetto per l'app con il plugin `QFieldSync <https://plugins.qgis.org/plugins/qfieldsync/>`__
#. Copiare il progetto QField sul mobile

.. warning:: Il progetto deve essere nel **Internal storage** (non in una scheda SD) per modificare i dati.

Il plugin QFieldSync funziona anche dal progetto QField al progetto *Desktop*.


Vantaggi e svantaggi
-----------------------------------
..
    TODO: Ordinare le idee

* È possibile di vedere raster layer con QField. 

.. hint:: Sceglie il Geopackage agli altri formati come TIF per esempio per il raster affinché il caricamento sia più veloce.

* L'app è maneggevole con la possibilità di personnalizzare il modulo degli attributi sul Desktop. 
* Durante la modifica, la disattivazione della visualizzazione delle coordinate tieniti sullo schermo i valori "__Infinity__" per X e Y.
