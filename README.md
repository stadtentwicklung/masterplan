# :world_map: Masterplan Cottbuser Ostsee 3.0
:white_check_mark: Georeferenziertes Rendering (Rasterbild) erstellen und als Web-Map publizieren mit Standortermittlung.

## :computer: Link [https://github.com/stadtentwicklung/map1)

This link above shows the original repository with a detailed README with more material of how to create such a map in GIS on desktop.

Here are some new information provided about the render-pipeline and the raster-look.   

### :camera_flash: Webmap 2.0: [https://stadtentwicklung.github.io/masterplan/]
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/masterplan/master/img/update.JPG)

### :camera_flash: Webmap 1.0: [https://stadtentwicklung.github.io/map1/]
![Screenshot der GitHub-Pages App](https://raw.githubusercontent.com/stadtentwicklung/map1/master/img/screenshot.JPG) 

## :rocket: Entstehungsprozess:

### :compass: Ausgangslage:
Der 1. [Masterplan Cottbuser Ostsee](https://www.cottbus.de/verwaltung/strukturentwicklung/ostsee/) (MaplOS) wurde vor ca. 15 Jahren mit AutoCAD erstellt. Das Projekt hat während dieser Zeit über 250 Layer angesammelt. Das dargestellte Gebiet des 3. Updates des MaplOS (MaplOS3) ist von 100 km&sup2; auf 180 km&sup2; gewachsen. Das Layout des Masterplans wurde auf ein DIN A1 Format gesetzt, womit die Darstellung den Maßstab 1:20.000 erhält. Diese beiden wichtigen Parameter orientieren sich an der Historie des Projektes. (1) Eine verbesserte Lesbarkeit trotz Vergrößerung der Gesamtfläche, (2) die dargestellten Elemente müssen verifizierbar sein, (3) die Anzahl der Datei-Layer auf ein überschaubares Maß reduzieren und (4) eine plastischere Visualisierung sind u.a. Anforderungen an den Relaunch. Technisches Ziel ist die Erhöhung der informativen und illustrativen Qualität des Plans. Der Plan muss als Ausdruck, aber auch auf Displays überzeugen. Auf Displays kann der Ausschnitt eines Dokument vergrößert werden. Zu einer einheitlichen Gesamtwirkung kommt das Kriterium Detailaussagen hinzu.

### :computer: Starter-Software:
Der MaplOS3 wurde wieder in AutoCAD Map 3D (ACM) technisch konstruktiv weiterentwickelt. ACM eignet sich sehr gut für eine Entwurfsgestaltung zwischen CAD und GIS mit großen Datenmengen. Der MaplOS3 enthält ca. 50.000 Einzelelemente. Werden die abgebildeten Gebäude dazugerechnet, verdoppelt sich die Anzahl auf über 100.000 (QGIS errechnet beim Einlesen einer .dwg oder .dxf die Anzahl der importierten Elemente). ACM bleibt dabei überwiegend performant und robust. Das Verschieben oder die individuelle Anpassung von Vektoren geht schneller als z.B. in QGIS. Die Arbeit mit georeferenzierten Inhalten läuft im Gegensatz z.B. zu Vectorworks ohne mehrere Nullpunkte. Außerdem lesen viele Programme .dwg- oder .dxf-Dateien problemlos ein.

# :world_map: Masterplan Cottbuser Ostsee 3.0
:white_check_mark: Georeferenziertes Rendering (Rasterbild) erstellen und als Web-Map publizieren mit Standortermittlung.

This repo only includes the app for polish visitors.

## :computer: Link to original (german) [https://github.com/stadtentwicklung/map1]

This repository above has a detailed README with more material of how to create such a map in GIS on desktop.
Some new information about inovations in the render-pipeline are in this link down:

## :computer: Link to the update (german) [https://github.com/stadtentwicklung/masterplan/]

### :coffee::coffee::coffee: by [Stefan](https://github.com/stefanstoehr)
