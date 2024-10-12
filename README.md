<a name="oben"></a>

<div align="center">

|[:skull:ISSUE](https://github.com/frankyhub/Stempel-lasern/issues?q=is%3Aissue)|[:speech_balloon: Forum /Discussion](https://github.com/frankyhub/Stempel-lasern/discussions)|[:grey_question:WiKi](https://github.com/frankyhub/Stempel-lasern/wiki)||
|--|--|--|--|
| | | | |
|![Static Badge](https://img.shields.io/badge/RepoNr.:-%2009-blue)|<a href="https://github.com/frankyhub/Stempel-lasern/issues">![GitHub issues](https://img.shields.io/github/issues/frankyhub/Stempel-lasern)![GitHub closed issues](https://img.shields.io/github/issues-closed/frankyhub/Stempel-lasern)|<a href="https://github.com/frankyhub/Stempel-lasern/discussions">![GitHub Discussions](https://img.shields.io/github/discussions/frankyhub/Stempel-lasern)|<a href="https://github.com/frankyhub/Stempel-lasern/releases">![GitHub release (with filter)](https://img.shields.io/github/v/release/frankyhub/Stempel-lasern)|
|![GitHub Created At](https://img.shields.io/github/created-at/frankyhub/Stempel-lasern)| <a href="https://github.com/frankyhub/Stempel-lasern/pulse" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/badges/shields" />| <a href="https://github.com/frankyhub/Stempel-lasern/graphs/traffic"><img alt="ViewCount" src="https://views.whatilearened.today/views/github/frankyhub/github-clone-count-badge.svg">  |<a href="https://github.com/frankyhub?tab=stars"> ![GitHub User's stars](https://img.shields.io/github/stars/frankyhub)|
</div>







# Stempel lasern

Inhaltsverzeichnis

[Einleitung](/README.md#Einleitung)

[Inkscape](/README.md#Inkscape)

[Lasercutter](/README.md#Lasercutter)

[3D-Druck](/README.md#3D-Druck)

[Montage](/README.md#Montage)

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

   <br>  

![stempel1.png](/pic/stempel1.png)

<br>

Möchte man einen Stempel mit einem Bild erstellen, wird das Bild in Inkscape importiert. 
Inkscape beinhaltet ein Werkzeug, mit dem sich ein Bitmap-Bild in ein Pfad-Element umwandeln lässt. Generell kann man sagen, je höher der Anteil dunkler Pixel im Bitmap ist, desto höher ist die Vektorisierungsleistung.
Importiere das Bild, das du vektorisieren willst mit "Datei + Impotieren" und bestätige mit "Öffnen".
Die Grundeinstellungen können mit OK übernommen werden.

<br>

![bild1.png](/pic/bild1.png)

<br>

Das Bitmap wird geladen:

<br>

![bild2.png](/pic/bild2a.png))

<br>

Das Bitmap markieren und mit "Pfad Bitmap nachzeichnen" oder mit  Umschalt  +  Alt  +  B  -Taste das Fenster Bitmap nachzeichnen öffnen.

<br>

![Bild2](/pic/bild2.png)

<br>


Wenn wir jetzt in das Zeichnen-Fenster wechseln, sehen wir das Bitmap und die vektorisierte Grafik.

<br>

![Bild3](/pic/bild4.png)

<br>

Wählen wir jetzt das "Bearbeiten der Knoten" Werkzeug aus oder betätigen die  N  -Taste, können wir die Pfade bearbeiten oder die Vektor-Grafik speichen und in andere Programme (Lightburn, Easy Cut Studio...) importieren.

---

## Lasercutter
Jetzt impotieren wir die Vektorgrafik in die Lasercutter Software **Lightburn**. In Lightburn werden jetzt die Ebenen Schneiden und Gravieren mit den jeweiligen Parameter Geschwindigkeit und Leistung festgelegt. 

<br>

![lk1](/pic/lk1.png)

<br>

Wir stellen die Cut- und die Gravur Ebene ein.

<br>

![lk2](/pic/lk2.png)

<br>


Mit der Vorschau lässt sich das Ergebnis vorab überprüfen. Die dunkelen Flächen werden gelasert.

<br>

![lk3](/pic/lk3.png)

<br>

---

## 3D-Druck
Mit einem 3D-Drucker erstellen wir den Stempelkörper. Mit dem **Openscad** Programm  "Stempel_Auswahl.scad" stehen uns 3 unterschiedliche Stempelformen zur Verfügung:

<br>

![3D](/pic/3d.png)

<br>


Für das runde Stempelmotiv wählen wird die runde Vorlage.

<br>

![3D2](/pic/3d2.png)

<br>

Jetzt können wir die 3D-Zeichnung slicen und drucken

<br>

![3D2](/pic/3dsl1.png)

<br>


---

## Montage
Nach dem Lasern des Stempelgummis und dem Erstellen des Stempelkörpers erfolgt die Montage. Den Stempelgummi kleben wir mit Sekundenkleber auf den Stempelkörper. Dabei beachten wir die Lage des Stempelgummis. 
Die Vorderseite des Stempelkörpers ist markiert.

<br>

![3Dm](/pic/3dm.png)




---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>  

---


