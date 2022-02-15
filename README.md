# :world_map: Masterplan Cottbuser Ostsee
:white_check_mark: Georeferenziertes Rendering erstellen und als Web-Map publizieren mit Standortermittlung.

This repository is an update of:
## :computer: Link [https://github.com/stadtentwicklung/map1)

Check the link above for detailed information.

### :camera_flash: WebMapApp-Screenshot:
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/map1/master/img/screenshot.JPG) 

## :rocket: Entstehungsprozess:

### :compass: Ausgangslage:
Der 1. [Masterplan Cottbuser Ostsee](https://www.cottbus.de/verwaltung/strukturentwicklung/ostsee/) (MaplOS) wurde vor ca. 15 Jahren mit AutoCAD erstellt. Das Projekt hat während dieser Zeit über 250 Layer angesammelt. Das dargestellte Gebiet des 3. Updates des MaplOS (MaplOS3) ist von 100 km&sup2; auf 180 km&sup2; gewachsen. Das Layout des Masterplans wurde auf ein DIN A1 Format gesetzt, womit die Darstellung den Maßstab 1:20.000 erhält. Diese beiden wichtigen Parameter orientieren sich an der Historie des Projektes. (1) Eine verbesserte Lesbarkeit trotz Vergrößerung der Gesamtfläche, (2) die dargestellten Elemente müssen verifizierbar sein, (3) die Anzahl der Datei-Layer auf ein überschaubares Maß reduzieren und (4) eine plastischere Visualisierung sind u.a. Anforderungen an den Relaunch. Technisches Ziel ist die Erhöhung der informativen und illustrativen Qualität des Plans. Der Plan muss als Ausdruck, aber auch auf Displays überzeugen. Auf Displays kann der Ausschnitt eines Dokument vergrößert werden. Zu einer einheitlichen Gesamtwirkung kommt das Kriterium Detailaussagen hinzu.

### :computer: Starter-Software:
Der MaplOS3 wurde wieder in AutoCAD Map 3D (ACM) technisch konstruktiv weiterentwickelt. ACM eignet sich sehr gut für eine Entwurfsgestaltung zwischen CAD und GIS mit großen Datenmengen. Der MaplOS3 enthält ca. 50.000 Einzelelemente. Werden die abgebildeten Gebäude dazugerechnet, verdoppelt sich die Anzahl auf über 100.000 (QGIS errechnet beim Einlesen einer .dwg oder .dxf die Anzahl der importierten Elemente). ACM bleibt dabei überwiegend performant und robust. Das Verschieben oder die individuelle Anpassung von Vektoren geht schneller als z.B. in QGIS. Die Arbeit mit georeferenzierten Inhalten läuft im Gegensatz z.B. zu Vectorworks ohne mehrere Nullpunkte. Außerdem lesen viele Programme .dwg- oder .dxf-Dateien problemlos ein.
