<a name="oben"></a>
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
Inkscape kann Texte und Grafiken verarbeiten. Einen Stempel mit Text und einem Logo zu erstellen sind so möglich. 
Im nachfolgenden Beispiel erstellen wir erst eine Vorlage mit Text und im 2. Beispiel eine Vorlage mit einer Grafik.

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

    

![stempel1.png](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/stempel1.png)

Möchte man einen Stempel mit einem Bild erstellen, wird das Bild in Inkscape importiert. 
Inkscape beinhaltet ein Werkzeug, mit dem sich ein Bitmap-Bild in ein Pfad-Element umwandeln lässt. Generell kann man sagen, je höher der Anteil dunkler Pixel im Bitmap ist, desto höher ist die Vektorisierungsleistung.
Importiere das Bild, das du vektorisieren willst mit "Datei + Impotieren" und bestätige mit "Öffnen".
Die Grundeinstellungen können mit OK übernommen werden.

![bild1.png](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/bild1.png)

Das Bitmap wird geladen:

![bild2.png](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/bild2a.png))

Das Bitmap markieren und mit "Pfad Bitmap nachzeichnen" oder mit  Umschalt  +  Alt  +  B  -Taste das Fenster Bitmap nachzeichnen öffnen.

![Bild2](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/bild2.png)


Wenn wir jetzt in das Zeichnen-Fenster wechseln, sehen wir das Bitmap und die vektorisierte Grafik.

![Bild3](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/bild4.png)

Wählen wir jetzt das "Bearbeiten der Knoten" Werkzeug aus oder betätigen die  N  -Taste, können wir die Pfade bearbeiten oder die Vektor-Grafik speichen und in andere Programme (Lightburn, Easy Cut Studio...) importieren.

---

## Lasercutter
Jetzt impotieren wir die Vektorgrafik in die Lasercutter Software **Lightburn**. In Lightburn werden jetzt die Ebenen Schneiden und Gravieren mit den jeweiligen Parameter Geschwindigkeit und Leistung festgelegt. 

![lk1](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/lk1.png)

Wir stellen die Cut- und die Gravur Ebene ein.

![lk2](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/lk2.png)

Mit der Vorschau lässt sich das Ergebnis vorab überprüfen. Die dunkelen Flächen werden gelasert.

![lk3](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/lk3.png)

---

## 3D-Druck
Mit einem 3D-Drucker erstellen wir den Stempelkörper. Mit dem **Openscad** Programm  "Stempel_Auswahl.scad" stehen uns 3 unterschiedliche Stempelformen zur Verfügung:

![3D](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/3d.png)

Für das runde Stempelmotiv wählen wird die runde Vorlage.

![3D2](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/3d2.png)

Jetzt können wir die 3D-Zeichnung slicen und drucken

![3D2](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/3dsl1.png)

---

## Montage
Nach dem Lasern des Stempelgummis und dem Erstellen des Stempelkörpers erfolgt die Montage. Den Stempelgummi kleben wir mit Sekundenkleber auf den Stempelkörper. Dabei beachten wir die Lage des Stempelgummis. 
Die Vorderseite des Stempelkörpers ist markiert.

![3Dm](https://github.com/frankyhub/Stempel-lasern/blob/main/pic/3dm.png)



<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>


 
---


