Input
==================================

.. image:: img/logo_input.png
  :align: center
  :scale: 150

Un GIS mobile app sviluppato da `Lutra Consulting <https://www.lutraconsulting.co.uk/>`__.


Installazione
----------------------------------

* Creare un account su https://public.cloudmergin.com/ (il account gratuito dà diritto a 100 MB di spazio di archiviazione)
* Scaricare l'applicazione sul mobile
* Installare il plugin mergin dal QGIS public repertory su QGIS Desktop

.. note:: È possibile che il plugin sia completamente installato dopo avere riavviare QGIS.


Funzionamento
-------------------------------------

Input pertanto utiliza il servizio d'archiviazione Cloud, Mergin, per la sincronizzazione dei dati tra QGIS e l'app.

.. image:: img/input_funzionamento_generale.png

* Creare il progetto QGIS con i layers (preferisce il Geopackage), il style, il modulo d'attributi, ...

.. note:: Il sistema di coordinate di riferimento del progetto per usare il GPS deve essere il WGS84/Pseudo-Mercator (EPSG:3857). In caso contrario, la mappa è centrata alle coordinate predefinite, ad esempio al punto (0,0) in WGS84.

* Configurare il plugin nel **Browser panel** con gli impostazioni dell'account

.. image:: img/mergin_plugin_init.JPG
    :align: center

* Creare un nuovo progetto Mergin (possibilità di creare da un directory locale o un progetto vuoto)
* Mergin va sincronizzando il progetto Mergin con il progetto locale
* Connettersi all'account sull'applicazione Input
* Il progetto è disponibile sull'app, nella sezione *I miei progetti*
* Scaricare il progetto sul telefono.

.. image:: img/input_get_mergin_project.gif
  :scale: 50

* Aprire questo nella *Home page*


.. note:: Quando c'è una modifica sul telefono o una sincronizzazione sul Desktop, lo statuto cambia nella pagina del progetto (*I miei progetti*, *Condiviso*) con una pittogramma di sincronizzazione.


Funzionalità
+++++++++++++++++++++

* Aggiunta di un'entità a un layer selezionato
* Modifica della geometria e degli attributi non geografici di un'entità
* Identificazione di un'entità geografica

.. image:: img/input_identify_entity.png
  :scale: 50

* Posizionamento di un punto con il GPS
* Tracciare linee o poligoni monitorando la posizione GPS

.. hint:: Selezionare un layer attivo si fatto differamente che su QGIS o QField

.. image:: img/input_get_active_layer.png


Vantaggi e svantaggi
----------------------------------

.. raw:: html

    <style>
        th,td{
            border: 1px solid black;
            padding: 5px;
        }

        th{
            background-color:#cccccc;
        }
    </style>
    <table style="border: 1px solid #000000;">
        <tr style="text-align:center;"><th>Vantaggi</th><th>Svantaggi</th></tr>
        <tr>
        <td><ul>
        <li>Rilievo offline possibile</li>
        <li>Sincronizzazione abbastanza veloce tra il rilievo e il progetto Desktop e molto veloce senza immagini</li>
        </ul></td>
        <td><ul>
        <li>Il vincolo *not null* non funziona sull'app, tranne i campi auto generati</li>
        <li>Non supporta i relazioni 1->n</li>
        <li>La modifica dei layers non geografici non è sviluppata</li>
        <li>I percorsi degli attaccamenti, per esempio gli immagini, non cambiano dopo sincronizzazione sul computer</li>
        <li>No checkbox (è sostituito da un switch con un text area)</li>
        </ul></td>
    </tr></table>


I link utili
------------------------------

#. https://inputapp.io/
#. https://github.com/lutraconsulting/input/blob/master/docs/users/introduction.md
#. https://github.com/lutraconsulting/input/blob/master/docs/developers/manual_test_plan.md
#. https://www.lutraconsulting.co.uk/blog/2020/02/14/survey-qgis-input/
#. https://public.cloudmergin.com/ 
