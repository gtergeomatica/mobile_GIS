IntraMap
==================================

.. image:: img/logo_roam.png
  :align: center
  :scale: 150


IntraMaps Roam è un colletore di dati, sviluppato su Windows. Oggigiorno, non esiste una versione stabile dell'applicazione, disponibile su Windows e Linux.


Installazione
---------------------------------

L'applicazione può essere installata su Windows con un installatore o un pachetto binario precompilato (https://roam-docs.readthedocs.io/en/latest/).

.. warning:: L'app non funziona con i sistemi Windows RT.

Su Linux, l'app viene eseguita dalla sorgente.


Funzionamento
---------------------------------

* Creare un progetto con **Roam Config Manager.exe**

.. image:: img/roam_config_home.PNG

* Nel repertory creato da Roam, il repertory **_data** contiene i dati specifi del progetto
* Aprire il progetto in QGIS tramite l'intefaccia di **Roam Config Manager**
* Aggiungere i layers in QGIS
* Salvare il progetto in QGIS
* Nel **Roam Config Manager**, creare un nuovo form degli attributi nella sezione *Form*

.. image:: img/roam_form_manager.PNG
  :scale: 75

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

.. image:: img/roam_main_screen_info.PNG
  :scale: 75

* Localizzazione GPS e acquisizione della posizione
* Form generato automaticamente
* Cercare un'entità secondo determini campi
* Monitorare la posizione GPS


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
        <li>Personalizzazione del form</li>
        <li>I vincoli funzionano</li>
        </ul></td>
        <td><ul>
        <li>App ancora in fase di sviluppo</li>
        <li>Non esiste per Android</li>
        </ul></td>
    </tr></table>


I link utili
----------------------------------

#. https://github.com/roam-qgis/Roam
#. https://roam-docs.readthedocs.io/en/latest/
