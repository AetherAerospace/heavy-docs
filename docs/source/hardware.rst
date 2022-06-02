Hardware.:
==========

Metal Gear Micro Servo.:
^^^^^^^^^^^^^^^^^^^^^^^^^
    Servos werde durch das Senden eines elektrischen Impulses mit variabler Breite oder einer Impulsbreitenmodulation durch die Steuerleitung gesteuert. Hierbei existiert ein minimaler Impuls, ein maximaler Impuls und eine Wiederholungsrate. Die Flexibilität dieser Servo Motoren beträgt 180°. Der Servomotor erwartet alle 20 Millisekunden einen Impuls, dies ist sehr wichtig da wir bei einer Rakete so schnell wie möglich in der Lage sein müssen über die Servoren die Nozzle/Fins zu steuern.


.. list-table::

   * - .. figure:: /image/hardware/hardware1.png

     - .. figure:: /image/hardware/hardware2.png





mpu6050 - Gyro.:
^^^^^^^^^^^^^^^^
    Der mpu6050 ist ein 6-Achsen-Bewegungserfassungsgerät, welches für geringen Stromverbrauch und hoher Leistung entwickelt wurde. Zudem ist er sehr klein gehalten und ermöglicht uns viel Spielraum beim Einbau des Teils.  Er besteht aus einer 16 – Bit – Analog – Digital – Wandler – Hardware, welche es uns ermöglicht dreidimensionale Bewegungen gleichzeitig zu erfassen welches ein Muss bei der Steuerung unserer Rakete ist.


.. list-table::

   * - .. figure:: /image/hardware/hardware3.png

     - .. figure:: /image/hardware/hardware4.png






Motoren.:
^^^^^^^^^
    Da wir uns entschlossen die Rakete durch Luft anzutreiben benötigten wir dafür motoren. Zum Glück hatten wir einen sich für Drohnen Interessierten in unserer Gruppe, welcher uns die Motoren zur Verfügung stellte. Die Motoren bestanden aus Plastik und wogen zudem nichts was unserem Ideal entsprach.


.. list-table::

   * - .. figure:: /image/hardware/hardware5.png

     - .. figure:: /image/hardware/hardware6.png





LoRa32.:
^^^^^^^^
    |pic1| Der TTGO Lora32 ist eine ESP32 Board, welches über ein integriertes LoRa module und einen SSD1306 LCD-Display verfügt. Da es sich hierbei um 2 Geräte handelt kann man das eine OnBoard einbauen und das andere in diesem Fall auf der Ground – Station anbauen. Dieses können miteinander kommunizieren und sich Daten hin und - zurückschicken.

.. |pic1| image:: /image/hardware/hardware7.png
   :width: 700px
   :height: 520px
   :scale: 100 %


ESP32.:
^^^^^^^
    Ein ESP32 ist ein kostengünstige und mit geringem Leistungsbedarf ausgeführte 32-Bit-Mikrocontrollerfamilie. Diese Mikrocontroller ermöglichen durch ihre Bauweise und die Vernetzung von netzwerkbasierten Aktuatoren und Sensoren. Dadurch dient uns der ESP32 in der Rakete sozusagen als Herzstück, durch welches es und mit der Rakete kommunizieren lässt.


.. list-table::

   * - .. figure:: /image/hardware/hardware8.png

     - .. figure:: /image/hardware/hardware9.png



CUQI GY - BMP280.:
^^^^^^^^^^^^^^^^^^
    Das CUQI GY-BMP280 Barometer ermöglicht es uns die Luftfeuchtigkeit als auch die Temperatur auf verschiedenen Höhenspiegelleveln zu messen. Dies soll uns ermöglichen Daten über den Flug der Rakete zu sammeln und daraus später genauere Informationen herauszufinden.

.. list-table::

   * - .. figure:: /image/hardware/hardware10.png

     - .. figure:: /image/hardware/hardware11.png