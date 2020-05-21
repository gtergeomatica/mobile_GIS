Input
==================================

.. image:: img/logo_input.png

Un GIS mobile app sviluppato da Lutra Consulting (https://inputapp.io/).


Installazione
----------------------------------

* Creare un account su https://public.cloudmergin.com/ (il account gratuito dà diritto a 100 MB di spazio di archiviazione)
* Scaricare l'applicazione sul mobile
* Installare il plugin mergin dal QGIS public repertory su QGIS Desktop

.. note:: È possibile che il plugin sia completamente installato dopo avere riavviare QGIS.

* Configurare il plugin nel **Browser panel** con gli impostazioni dell'account
* Creare un nuovo progetto Mergin (possibilità di creare da un directory locale)
* Mergin va sincronizzando il progetto Mergin con il progetto locale
* Connettersi all'account sull'applicazione Input
* Il progetto è disponibile sull'app, nella sezione "I miei progetti"


Funzionamento
-------------------------------------

Input pertanto utiliza il servizio d'archiviazione Cloud, Mergin, per la sincronizzazione dei dati tra QGIS e l'app.

.. image:: img/input_funzionamento_generale.png


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
        <li></li>
        </ul></td>
        <td><ul>
        <li>La modifica dei layers non geografici non è sviluppata</li> 
        <li>No checkbox (è sostituito da un switch con un text area)</li>
        </ul></td>
    </tr></table>