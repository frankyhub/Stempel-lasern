# Stempel lasern

Inhaltsverzeichnis

[Einleitung](https://github.com/frankyhub/Stempel-lasern/blob/main/README.md#Einleitung)

[Inkscape](https://github.com/frankyhub/Stempel-lasern/blob/main/README.md#Inkscape)

[Lasercutter](https://github.com/frankyhub/Stempel-lasern/blob/main/README.md#Lasercutter)

[3D-Druck](https://github.com/frankyhub/Stempel-lasern/blob/main/README.md#3D-Druck)

[Montage](https://github.com/frankyhub/Stempel-lasern/blob/main/README.md#Montage)

----------


## Einleitung
Ein Stempel kann mit dem Zeichenprogramm Inkscape, einem Lasercutter und einem 3D-Drucker selbst hergestellt werden.

---

## Inkscape
Mit dem Vektor-Zeichenprogramm Inkscape wird die Stempelvorlage erstellt, die z. B. auf Stempelgummi gelasert werden kann. Die nachfolgenden Schritte berscheiben die Funktion.

1. Text schreiben.
2. Schriftart und Größe festlegen.
3. Text spiegeln.
4. Evtl. keine Kontur aber Füllung auswählen (Text wird schlanker).
5. In der Größe des gewünschten Stempels einen Rahmen um den Text ziehen.
6. Text in den Rahmen horizontal und vertikal zentrieren.
7. Text und Rahmen mit Shift-Taste auswählen und in Pfade umwandeln.
8. Die Datei in LightBurn importieren.
9. Mit "G=100, L=45 und Modus Füllen" lasern.
10. Stempel-Vorschau in LightBurn:

!(Stempel1)[stempel1.png)

Möchte man einen Stempel mit einem Bild erstellen, wird das Bild in Inkscape importiert. 
Inkscape beinhaltet ein Werkzeug, mit dem sich ein Bitmap-Bild in ein Pfad-Element umwandeln lässt. Generell kann man sagen, je höher der Anteil dunkler Pixel im Bitmap ist, desto höher ist die Vektorisierungsleistung.
Lade oder importiere das Bild, das du vektorisieren willst mit "Datei + Impotieren" und betästige mit "Öffnen".
Die Grundeinstellungen können mit OK übernommen werden.

!(Bild1)[bild1.png)

Das Bitmap wird geladen:

!(Bild2)[bild2.png)

Das Bitmap markieren und mit "Pfad Bitmap nachzeichnen" oder mit  Umschalt  +  Alt  +  B  -Taste das Fenster Bitmap nachzeichnen öffnen.

!(Bild3)[bild3.png)

Wenn wir den "Aktualisieren-Button" betätigen wird die Vorschau geladen.

!(Bild4)[bild4.png)

Wir können jetzt den Helligkeitsschwellwert optimieren und ggf. das Bitmap invertieren. Nach betätigen des "Anwenden" Buttons wird die Ansicht aktualisiert.

!(Bild5)[bild5.png)

Wenn wir jetzt in das Zeichnen-Fenster wechseln, sehen wir das Bitmap und die vektorisierte Grafik.

!(Bild6)[bild6.png)

Wählen wir jetzt das "Bearbeiten der Knoten" Werkzeug aus oder betätigen die  N  -Taste, können wir die Pfade bearbeiten oder die Vektor-Grafik speichen und in andere Programme (Lightburn, Easy Cut Studio...) importieren.

!(Bild7)[bild7.png)

Wenn die Füllung entfernt wird, sieht man den Umriss der Zeichnung.

!(Bild8)[bild8.png)


---

## Lasercutter
Jetzt impotieren wir die Vektorgrafik in die Lasercutter Software **Lightburn**. In Lightburn werden jetzt die Ebenen Schneiden und Gravieren festgelegt mit den jeweiligen Parameter Geschwindigkeit und Leistung festgelegt. 


---

## 3D-Druck
Mit einem 3D-Drucker erstellen wir den Stempelkörper. Mit dem Programm **Openscad** stehen uns 3 unterschiedliche Stempelformen zur Verfügung:

!(3D)[3d.png) 



---

## Montage
Nach dem Lasern des Stempelgummis und dem erstellen des Stempelkörpers erfolgt die Montage. Den Stempelgummi kleben wir mit Sekundenkleber auf den Stempelkörper. Dabei beachten wir die Lage des Stempelgummis. 
Die Vorderseite des Stempelkörpers ist markiert.

 !(3Dm)[3dm.png)
 
---

Ein Stempel wird in mehreren Arbeitsschritten erstellt:
