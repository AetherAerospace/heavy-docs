Software.:
==========

Welche Software ?
^^^^^^^^^^^^^^^^^

Software Überblick.:
""""""""""""""""""""

    Da unser Projekt sehr wahrscheinlich das erste seiner Art ist, war es uns nicht möglich bloß irgendeine existierende Software von irgendwo zu kopieren oder uns in jeglicher Art inspizieren zu lassen. Dabei schränke ich mich nur auf den selbstbenötigten Code ein und nehme an das zuvor in die Sprache integrierte Libaries selbstverständlich sind. Folgende Sprachen/Ressourcen wurden für unser Projekt verwendet und ermöglichen die Kommunikation in unserer Rakete.


.. list-table::

   * - .. figure:: /image/c++.png

     - .. figure:: /image/c.png

   * - .. figure:: /image/html_logo.png

     - .. figure:: /image/shell.jpg







Software für was ?
^^^^^^^^^^^^^^^^^^^
    Wo brauchen wir unsere Software eigentlich? Wir können den Aufbau der Rakete als auch die dafür benötigte Software in zwei einfach Komponenten zerteilen: **Ground-Station** und **Onboard**



Ground - Station.:
""""""""""""""""""
    Die Ground Station ist eine relativ übersichtliche Station. Sie verschafft uns die Möglichkeit Daten der Rakete während des Fluges zu empfangen und hostet zugleich eine Interaktive Webseite, welche es ermöglichen soll, die Rakete wie zuvor in $ 2.0 Kommunikation besprochen.


OnBoard.:
"""""""""
    Unter OnBoard Station können sie alle benötigten Komponenten zusammenfassen, die Sich auf der Rakete befinden und verwendet werden, um Daten zu sammeln und später auszuwerten. Zuallererst befindet sich auf der Onboard Station ein Baro Sensor, welcher es uns ermöglicht den Höhenunterschied der Rakete zu erfassen. Das ist sehr wichtig da die dadurch erhaltenen Daten sofort an unser Data Logging weitergeschickt wird welches dafür sorgt das die vom Baro Sensor erhaltenen Telemetrie daten auf einer SD-Karte aufgeschrieben werden und später verwendet werden können, um sich einen genaueren Überblick über den Flug der Rakete zu verschaffen. Zudem werden die vom Baro Sensor erfassten Daten sofort über das LoRa Modul welches wie zuvor besprochen eine Kommunikation zwischen Ground und OnBoard Station bietet und es uns ermöglicht Daten entweder Auf dem Monitor der Ground Station oder über die Webseite ablesen





Software - GitHub.:
^^^^^^^^^^^^^^^^^^^^

    Um es zu ermöglichen einen genauen Überblick über das Projekt zu haben und bei möglichen Fehlern genau zu sehen was schiefgelofen ist wurde bei diesem Projekt auf GitHub zurückgegriffen. GitHub ist ein webbasierter Dienst, der Entwicklern hilft, ihren Code zu speicher und zu verwalten sowie Änderung an ihrem Code zu verfolgen und zu kontrollieren.




    Auf dem von Felix Slama erstellten GitHub Repository können sie sich einen genaueren Überblick über das Projekt verschaffen. Mit der von uns verwendeten “GNU General Public License” steht innen der Code offen zu verfügung und sie können sämtlichen Code und Stl files übernehmen/überarbeiten/ändern. Natürlich nicht im Ursprungs Repository.

