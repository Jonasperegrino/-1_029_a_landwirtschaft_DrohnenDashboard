# Projektidee
Unser Ziel ist die Landwirte bei der Ernte von Sonderkulturen mit Drohnen zu unterstützen.
Dabei fungieren wir als Softwareanbieter für Landwirte und Drohnen-Dienstleister. Mit unserem Produkt kann der Kunde eine Drohne steuern und die so gewonnenen Daten auswerten, um eine detaillierte Karte der Erntefähigkeit seiner Kulturen zu erhalten.

In der harten Zeit des Corona-Virus ersparen wir den Landwirten so Zeit, die Gefahr sich draußen aufzuhalten und ermöglichen ein hoch effizientes Management des Ernteablaufes bei geringem Personalbedarf.

# Funktion
- Die Drohne wird mit einem Smartphone oder Tablet mit üblicher Software geflogen (dronedeploy, litchi, pix4d etc.) → Anleitung
- Die erzeugten Bilder werden zu einem georeferenzierten Orthophoto gestitcht (z.b. mit opendronemap)
- Aus dem Orthophoto wird ein Index/Score berechnet zur Erntefähigkeit
- Der Index/Score wird mit Koordinaten exportiert (geojson, csv…)
- Das Dashboard zeigt die Indexkarte an → Integration in vorhandene Lösungen (iframe)
