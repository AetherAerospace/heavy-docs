Design 2.0 - The Injector.:
===========================

Design 2.0 Überblick.:
^^^^^^^^^^^^^^^^^^^^^^

Was ist The Injector.:
""""""""""""""""""""""
   |pic1| Design 2.0 aka “The Injector” war unser zweiter Prototyp der Rakete. Da wir nun jedoch genug Daten aus unseren Vorherigen Tests gesammelt hatten wussten wir nun, worauf wir beim Design der Rakete unbedingt achten mussten. Als erstes entschieden wir und das Design der Rakete grundlegend komplett zu verändern. Die Rakete musste unter allen Umständen aerodynamischer sein, weniger wiegen und bessere Möglichkeiten für Kabelmanagement und später eingefügte Raketenteile haben. Um hier nicht auf weitere Motoren ausweichen zu müssen entschieden wir uns die Breite gewisser Teile auf eine Breite von 70mm zu drucken. Gewisse Teile wie TVM, TDM und TIM blieben jedoch auf einer Breite von 90mm, da diese auf keinen Fall brechen durften. Das Ziel von “The Injector” war es nun in der Lage zu sein den Air Flow der Rakete so kompakt und smart zu designen wie möglich. 

.. |pic1| image:: /image/TheInjector.png
   :width: 700px
   :height: 520px
   :scale: 100 %





Design 2.0 Struktur.:
^^^^^^^^^^^^^^^^^^^^^

EDM - Energy Delivery Module.:
""""""""""""""""""""""""""""""

   Das EDM – Energy Delivery Module welches zuvor bei Design 1.0 Persevirance nicht benötigt worden war, wurde nun bei “The Injector” eingefügt. Bei Design 1.0 wurde die Stromzufuhr extern abgeregelt. Dies wollten wir bei “The Injector” natürlich ändern. Um der Rakete zu ermöglichen, ohne Einfluss von außen Stromzufuhr zu haben implementierten wir das EDM so ziemlich an der Spitze der Rakete. Dies hatte mehrere Gründe. Einerseits war es bei einer Rakete sehr wichtig die Nase schwerer zu gestalten als den Rumpf und die Lenkung und die Kontrolle zu erleichtern. Andererseits würde die Positionierung des EDM an einer niedrigeren Position Auswirkungen auf unseren Luft Fluss haben. Um das EDM nun noch besser zu stabilisieren und Kabelführung einfacher zu gestalten entwarfen wir den Coupler. Dessen Aufgabe war es die Batterie in Position zu halten und Kabelführung in der Rakete zu vereinfachen und beinhaltet außerdem den Gyro Sensor.


**Main Part**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/edm/EDM1.png

     - .. figure:: /image/Design/Design2.0/edm/EDM2.png


**Coupler**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/edm/EDM3.png

     - .. figure:: /image/Design/Design2.0/edm/EDM4.png









EPM - Electronic Processing Module.:
""""""""""""""""""""""""""""""""""""

    Die Aufgabe des EPM bei “The Injector” war es die ganze Elektronik zu verstauen und diese Damit für die Rakete leicht zugänglich zu machen. Das EPM befindet sich direkt über dem EDM und beinhaltet die gesamte Elektronik außer den Gyro Sensor, welches sich im unteren Teil des EDM befindet.

.. list-table::

   * - .. figure:: /image/Design/Design2.0/epm/EPM1.png

     - .. figure:: /image/Design/Design2.0/epm/EPM2.png







TDM - Thrust Delivery Module.:
""""""""""""""""""""""""""""""

    Wie zuvor bei Persevirance dient das TDM - Thrust Delivery Module der Aufgabe die von uns verwendeten Motoren zu befestigen. Bei diesem Design versuchten wir aber im oberen Bereich des TDM mehr Platz zu schaffen, um der eingezogenen Luft die Möglichkeit zu geben sofort von den Motoren eingesogen zu werden.


**Bottom**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tdm/TDM1.png

     - .. figure:: /image/Design/Design2.0/tdm/TDM2.png


**Top**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tdm/TDM3.png

     - .. figure:: /image/Design/Design2.0/tdm/TDM4.png











TIM - Thrust Intake Module.:
""""""""""""""""""""""""""""


**VERSION 1.0:**

  Aus den von Persevirance erhaltenen Ergebnissen wussten wir das wir etwas am TIM ändern mussten. Unser erster Ansatz war es einen Kleinen Überhang zu erschaffen über den die Luft leichter in die Rakete geriet.  Erste Anläufe zeigten gute Ergebnisse, jedoch waren wir den von uns gewünschten Ziel noch weit entfernt.

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tim/version1/TIM1.png

     - .. figure:: /image/Design/Design2.0/tim/version1/TIM2.png






**VERSION 2.0:**

    Bei Version 2, nahmen wir das zuvor verwendete TIM und erhöhten den Bereich in den Luft in die Rakete eindringen könnte. Die dadurch erhaltenen Ergebnisse variierten nicht stark von den aus Version 1.0.

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tim/version2/TIM1.png

     - .. figure:: /image/Design/Design2.0/tim/version2/TIM2.png
   



**VERSION 3.0:**

   Um nun nicht wieder unsere gesamte Rakete umzu designen kam es zu einer erweiterten Version des TIM: ”Version 3.0”. Diese sprach mit dieser noch größeren und weiteren Öffnung noch mehr Luft an. Das Teil wurde zudem fast auf das doppelte des Vorherigen Designes erweitert. 

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tim/version3/TIM1.png

     - .. figure:: /image/Design/Design2.0/tim/version3/TIM2.png
   















TVC - Thrust Vectoring Module.:
"""""""""""""""""""""""""""""""

**VERSION 1.0:**

Das TVC - Thrust Vectoring Module der neuen Rakete unterschied sich in der Struktur und Kombination der Verwendeten Servo’s. Um nicht mehr die Aerodynamik durch die Servos zu verschlechtern, wurden diese in eigene Bereiche eingebaut, um so nicht mehr zu stören. Die benötigten Füße waren zu diesem Zeitpunkt noch nicht designend da wir uns noch in einer Testphase für das neue TVC befanden.

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/version1/TVC1.png

     - .. figure:: /image/Design/Design2.0/tvc/version1/TVC2.png






**VERSION 2.0:**

Version 2.0 des TVC hatte gewisse Vorteile gegenüber Version 1.0. Einerseits mussten wir nicht eigene Bereiche für die Servoren erstellen da diese in Design 2.0 Unter der Kreisförmigen Struktur verborgen waren. Andererseits waren die von uns benötigten Füße direkt am TVC angebunden und mussten nicht einzeln gedruckt werden. Dadurch nahm das Gewicht der Rakete ab, jedoch sankt dadurch unser Luftantrieb gewaltig ab da wir durch das offene untere Ende zu viel Luftausweich Möglichkeiten hatten.

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/version2/TVC1.png

     - .. figure:: /image/Design/Design2.0/tvc/version2/TVC2.png
   



**VERSION 3.0:**

Version 3.0 war wegen der Verschwendeter Luft Nötig, da verglichen zu Fins eine Nozzle viel mehr Luftausgangmöglichkeiten abblockt. Der Adapter für das Main TVC wär nötig um eine Folie einzuklemmen welche und ermöglichen würde den gesamten Luftstrom auf die Nozzle umzuleiten und dadurch maximale Effizienz zu erreichen. Jedoch erlangt die Rakete durch die große Nozzle zusätzliches Gewicht. Ein großes Risiko welches wir jedoch trotzdem eingehen mussten.



**Main TVC**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/version3/TVC1.png

     - .. figure:: /image/Design/Design2.0/tvc/version3/TVC2.png
   


**Adapter for TVC**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/version3/TVC3.png

     - .. figure:: /image/Design/Design2.0/tvc/version3/TVC4.png


**Nozzle Redesign Part 1**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/nozzle/redesign/version1/NOZZLE1.png

     - .. figure:: /image/Design/Design2.0/tvc/nozzle/redesign/version1/NOZZLE2.png


**Nozzle Redesign Part 2**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/nozzle/redesign/version2/NOZZLE1.png

     - .. figure:: /image/Design/Design2.0/tvc/nozzle/redesign/version2/NOZZLE2.png


**Nozzle Inner Ring Part 1**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/nozzle/inner/version1/NOZZLE1.png

     - .. figure:: /image/Design/Design2.0/tvc/nozzle/inner/version1/NOZZLE2.png


**Nozzle Inner Ring Part 2**

.. list-table::

   * - .. figure:: /image/Design/Design2.0/tvc/nozzle/inner/version2/NOZZLE1.png

     - .. figure:: /image/Design/Design2.0/tvc/nozzle/inner/version2/NOZZLE2.png

