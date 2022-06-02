Kommunikation
=============

Kommunikation Überblick.:
^^^^^^^^^^^^^^^^^^^^^^^^^

Zusammenfassung.:
"""""""""""""""""
    Die Kommunikation in unserem Projekt besteht aus drei Komponenten. Die Idee war es jeweils ein LoRa Module in der Rakete zu befestigen und das zweite LoRa Modul in der Groundstation anzubringen. Um dann noch mit dem Lora zu kommunizieren wurde ein Web-Interface erstellt, mit dem es uns möglich war, befehle per Knopfdruck an die Rakete zu senden und im Notfall eingreifen zu können. Das dritte Modul wird in der zweiten Stufe eingesetzt.
    Das verwendete Modul heißt TTGO ESP32 Lora32 V2.




TTGO Lora32.:
"""""""""""""
    Der TTGO Lora32 ist eine ESP32 Board, welches über ein integriertes LoRa module und einen SSD1306 LCD Display verfügt. Da es sich hierbei um 2 Geräte handelt kann man das eine Board einbauen und über das andere den aktuellen Status der Rakete abfragen.


Datenaustausch.:
""""""""""""""""
    Der Datenaustausch erfolgt über eine Punkt-zu-Punkt Kommunikation, bei welcher einer der TTGO Lora32 als Sender und der andere als Empfänger fungiert. Mithilfe des Integrierten Displays erhalten wir eine Art Visualisierung der Übertragenen Daten.


Was ist LoRa.:
""""""""""""""
    LoRa steht für Long Range und ist ein Low-Power Wide-Area Network (LPWAN) und verwendet eine breite Palette von Funkfrequenzen. Europaweit wird 868MHz verwendet. Dadurch ist es möglich mit LoRa-Technologie Daten über eine Strecke von bis zu 10km zu übertragen.



Kommunikation Funktion.:
^^^^^^^^^^^^^^^^^^^^^^^^

LoRa Kommunikation.:
""""""""""""""""""""
    |pic1|

.. |pic1| image:: /image/LoRa.png
   :width: 700px
   :height: 680px
   :scale: 100 %



LoRa Sender.:
"""""""""""""
    Der LoRa Sender der sich auf der Aether One Rakete befindet ist an einem ESP32 verbunden welche wiederum mit einem Gyroscope verkabbelt ist. 
    Die vom Gyroscope erhaltenen Daten werden dann an einerseits an eine Eingebaute SD gesendet um Daten später auszuwerten und andereseits an den LoRa Sender. 
    Die an den LoRa Sender gelangenden Daten werden dann wie in der zuvor veranschaulichten Grafik an den LoRa Receiver gesendet.


LoRa Receiver.:
"""""""""""""""
    |pic2| Der LoRa Receiver empfängt eingehende LoRa-Pakete und zeigt die empfangenen Messwerte auf einem laufendem Webserver an.
    Dieser laufende Webserver wird auf dem LoRa Receiver gehostet und ist durch ein erstelltes SSID verfügbar.
    Nun kann man sich in dieses SSID-Netzwerk mit einem von uns aus Sicherheitsgründen erstellten Password verbinden.
    Nun kann man über einen Webbrowser die jeweilige IP addresse des LoRa Receivers eingeben und gelangt somit auf das Web-Interface.

.. |pic2| image:: /image/LoRa2.png
   :width: 700px
   :height: 380px



Web-Interface.:
"""""""""""""""

    |pic3| Um aktiv am LoRa Datenaustausch teilnehmen zu können, erstellten wir ein Webinterface, welches direkt auf dem LoRa Sender gehostet wird.
    Das Web-Interface verfügt dabei über einen Hold-Thrust und Kill-Knopf.
    Der Hold-Thrust Knopf verhindert, dass die Geschwindigkeit des Motors verändert wird.
    Der Kill-Knopf ist dafür da, jederzeit die Motoren stoppen zu können und unkontrolliertes Steigen zu unterbinden.
    Zudem wird wie im untenstehenden Bild zu erkennen der derzeitige Wert der Sensoren abgebildet, welche im späteren Flug in regulierten Schritten aufgenommen werden und dann auf einer SD gespeichert werden.
    Womit wir dann im Weiterem eine für sie Lesbare Grafik erstellen werden.
    Um jedoch das worst Case Scenario zu vermeiden das unser Web Interface nicht mehr auf User Input reagieren sollte bauten wir einen weiteren Kill-Knopf auf dem Lora-Receiver Selbst ein.


.. |pic3| image:: /image/LoRa3.png
   :width: 200px
   :height: 380px
   :scale: 100 %