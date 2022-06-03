Hardware
========

Micro Servos:
^^^^^^^^^^^^^

    Servos werden durch das Senden eines elektrischen Impulses mit variabler Breite (Impulsbreitenmodulation) durch eine 
    Steuerleitung gesteuert. Hierbei existiert ein minimaler Impuls, ein maximaler Impuls und eine Wiederholungsrate. Servomotoren 
    ermöglichen uns das präzise Steuern unserer Raketen.

.. list-table::

   * - .. figure:: /image/hardware/hardware1.png

     - .. figure:: /image/hardware/hardware2.png

MPU6050 - Gyro:
^^^^^^^^^^^^^^^

    Der MPU6050 ist ein Bewegungserfassungsgerät, welches für geringen Stromverbrauch und hohe Leistung entwickelt wurde. 
    Zudem ist es sehr klein gehalten und ermöglicht uns viel Spielraum beim Einbau. Es besteht aus einer 16-Bit Analog-Digital-Wandler 
    Hardware, welche es ermöglicht, Beschleunigung und Neigung auf allen drei Achsen gleichzeitig zu erfassen. Diese Rohdaten werden
    vom Flightcode direkt in den PID-Controller gespeist und dort weiter verarbeitet.

.. list-table::

   * - .. figure:: /image/hardware/hardware3.png

     - .. figure:: /image/hardware/hardware4.png

Motoren:
^^^^^^^^

    Für den Antrieb unserer Rakete verwenden wir Brushless-DC Motoren, welche heutzutage vorallem in RC-Drohnen, Baumaschinen und anderen
    elektronischen Geräten zum Einsatz kommen. Bei Perseverance und The Injector fiel unsrere Wahl auf 2206 2600KV Motoren, welche aber bei 
    Endurance gegen leichtere und stärkere 1507 3600KV Motoren getauscht wurden.

.. list-table::

   * - .. figure:: /image/hardware/hardware6.png

     - .. figure:: /image/hardware/hardware12.jpg

ESP32-LoRa:
^^^^^^^^^^^

    Der TTGO Lora32 ist ein ESP32 Board, welches über ein integriertes LoRa Modul und SSD1306 OLED-Display verfügt. Der ESP32 ist ein
    funktionsreicher, für seine Größe leistungstarker und effizienter Mikrocontroller, weswegen er auch das Gehirn unserer Raketen ist.
    Auch für unsere Groundstation kommt solch ein Board zum Einsatz, um die reibungslose Kommunikation zwischen Luft und Boden sicherzustellen.

.. image:: /image/hardware/hardware7.png
   :width: 700px
   :height: 520px
   :scale: 100 %

BMP280:
^^^^^^^
    
    Das BMP280 Barometer ermöglicht es uns Temperatur und vorallem Luftdruck genau zu bestimmen. Durch den erfassten Luftdruck wird schließlich
    die aktuelle Höhe errechnet und im Flightcode mit einbezogen, um immer genaue Kontrolle über die Flughöhe zu haben.

.. list-table::

   * - .. figure:: /image/hardware/hardware10.png

     - .. figure:: /image/hardware/hardware11.png
