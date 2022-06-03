Software
========

Sprachen:
^^^^^^^^^

    Verwendete Sprachen:
        - C++ bzw. Arduino-C
        - JavaScript
        - Bash
        - CSS
        - HTML

    Der Großteil des Codes ist in C++ geschrieben. Die anderen Sprachen dienen zur Ergänzung in manchen Teilbereichen des Hauptcodes.

Software Unterteilung:
^^^^^^^^^^^^^^^^^^^^^^

    Natürlich müssen unsere Raketen auch irgendwie in der Lage sein, sich autonom Steuern zu können. Hier kommt unsere Software inside
    Spiel, welche wir in zwei Bereiche aufteilen.

Flightcode:
"""""""""""

    Der Flightcode ist das Herzstück unserer Raketen. Zu den wichtigsten Komponenten zählen vorallem der PID-Controller Code welcher 
    für die korrekte Ansteuerung der Servos zuständig ist, der LoRa-Communication Code welcher sicherstellt, dass stets Kommunikation
    zur Groundstation herrscht, der Power Control Code für die Ansteuerung der Motoren und natürlich der MPU Code, welcher für die korrekte
    Initialisierung und Ansteuerung des MPU6050 zuständig ist. Natürlich sind diese nur einige Kernkomponenten der kompletten Software, welche
    inzwischen über 1000 Zeilen Code umfasst.

Groundstation:
""""""""""""""

    Die Groundstation ist in ihrer Funktion sehr einfach. Sie verschafft uns die Möglichkeit, Daten der Rakete während 
    des Fluges zu empfangen. Die Station wurde ab The Injector ein fixer Bestandteil jeder unserer Raketen. Ein Sicherheitsaspekt
    der dadurch imlementiert wurde, ist die sofortige Terminierung des Fluges, sofern die Kommunikation zwischen Luft und Boden nicht
    mehr bestehen. Vor jedem Flug wird deshalb vom Code immer eine Check-Sequenz durchgangen, bei der sichergestellt wird, das die
    Kommunikation zwischen Luft und Boden stabil ist.

GitHub:
^^^^^^^

    Da alle unserer Teammitglieder sehr viel Wert auf Open Source legen, wird unser gesamter Code auf GitHub zur Verfügung gestellt.

    https://github.com/AetherAerospace
    
