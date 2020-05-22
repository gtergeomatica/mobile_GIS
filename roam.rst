IntraMap
==================================

.. image:: img/logo_roam.png
  :align: center


IntraMaps Roam è un colletore di dati, sviluppato su Windows. Oggigiorno, non esiste una versione stabile dell'applicazione, disponibile su Windows e Linux.


Installazione
---------------------------------

L'applicazione può essere installata su Windows con un installatore o un pachetto binario precompilato (https://roam-docs.readthedocs.io/en/latest/).

.. warning:: L'app non funziona con i sistemi Windows RT.

Su Linux, l'app viene eseguita dalla sorgente.


Funzionamento
---------------------------------

* Creare un progetto con **Roam Config Manager.exe**
* Nel repertory creato da Roam, il repertory **_data** contiene i dati specifi del progetto
* Aprire il progetto in QGIS tramite l'intefaccia di **Roam Config Manager**
* Aggiungere i layers in QGIS
* Salvare il progetto in QGIS
* Nel **Roam Config Manager**, creare un nuovo modulo degli attributi nella sezione *Form*

.. note:: Il modulo è solamente per i layers geografici

* Nella scheda *Design*, configurare il tipo di campo di riempimento per ogni attributo
* Salvare il progetto e aprire **Roam.exe**
* Caricare lo da l'elenco dei progetti

.. warning:: Gli elenchi creati da un altro layer non funzionano per questa prova.

L'app offre la possibilità di pubblicare il progetto su un server web. Gli utenti possono scaricare il progetto su loro computer.


Funzionalità
+++++++++++++++++++++

* Aggiunta di un'entità a un layer selezionato
* Modifica della geometria e degli attributi non geografici di un'entità
* Identificazione un'entità
* Localizzazione GPS e acquisizione della posizione
* Modulo generato automaticamente
* Configurazione il pannelli informativi


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
        <li>Grande interfaccia</li>
        </ul></td>
        <td><ul>
        <li>App ancora in fase di sviluppo</li>
        <li>Non esiste per Android</li>
        </ul></td>
    </tr></table>