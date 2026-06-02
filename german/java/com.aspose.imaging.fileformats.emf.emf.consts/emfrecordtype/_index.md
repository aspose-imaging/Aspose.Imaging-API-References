---
title: "EmfRecordType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die RecordType‑Aufzählung definiert Werte, die EMF‑Datensätze eindeutig identifizieren."
type: docs
weight: 38
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

Die RecordType‑Aufzählung definiert Werte, die EMF‑Aufzeichnungen eindeutig identifizieren. Diese Werte werden im Feld Type jeder Aufzeichnung bereitgestellt.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Dieser Datensatz definiert den Beginn der Metadatei und gibt ihre Eigenschaften an; ihren Inhalt, einschließlich der Abmessungen des eingebetteten Bildes; die Anzahl der Datensätze in der Metadatei; und die Auflösung des Geräts, auf dem das eingebettete Bild erstellt wurde. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven. |
| [EMR_POLYGON](#EMR-POLYGON) | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Scheitelpunkten besteht, die durch gerade Linien verbunden sind. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen Array verbindet. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven basierend auf der aktuellen Position. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Dieser Datensatz definiert eine oder mehrere gerade Linien basierend auf der aktuellen Position. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Dieser Datensatz definiert eine Reihe geschlossener Polygone. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Dieser Datensatz definiert die Fensterausdehnung. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Dieser Datensatz definiert den Fensterursprung. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Dieser Datensatz definiert die Viewport‑Ausdehnung. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Dieser Datensatz definiert den Viewport‑Ursprung. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Dieser Datensatz definiert den Ursprung des aktuellen Pinsels. |
| [EMR_EOF](#EMR-EOF) | Dieser Datensatz kennzeichnet das Ende der Metadatei. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Dieser Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Dieser Datensatz gibt Parameter des Prozesses an, bei dem logische Schriften zu physischen Schriften zugeordnet werden, was vom Font‑Mapper durchgeführt wird. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Dieser Datensatz definiert den Abbildungsmodus des Wiedergabe‑Geräte‑Kontexts. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Dieser Datensatz definiert den Hintergrund‑Mischmodus des Wiedergabe‑Geräte‑Kontexts. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Dieser Datensatz definiert den Füllmodus für Polygone. |
| [EMR_SETROP2](#EMR-SETROP2) | Dieser Datensatz definiert den binären Raster‑Operations‑Modus. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Dieser Datensatz definiert den Bitmap-Streckmodus. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Dieser Datensatz definiert die Textausrichtung. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Dieser Datensatz definiert die Farbkorrekturwerte für den Wiedergabegerätekontext unter Verwendung der angegebenen Werte. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Dieser Datensatz definiert die aktuelle Textfarbe. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Dieser Datensatz definiert die Hintergrundfarbe. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Dieser Datensatz definiert den Clipping‑Bereich des Wiedergabegerätekontexts anhand der angegebenen Offsets neu. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Dieser Datensatz definiert die Koordinaten der neuen aktuellen Position in logischen Einheiten. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Dieser Datensatz schneidet den aktuellen Clipping‑Bereich für den Wiedergabegerätekontext mit dem aktuellen Meta‑Bereich und speichert den kombinierten Bereich als neuen Meta‑Bereich. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Dieser Datensatz definiert einen neuen Clipping‑Bereich, der aus dem bestehenden Clipping‑Bereich abzüglich des angegebenen Rechtecks besteht. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Dieser Datensatz definiert einen neuen Clipping‑Bereich aus der Schnittmenge des aktuellen Clipping‑Bereichs und des angegebenen Rechtecks. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Dieser Datensatz definiert den Ansichtsbereich für den Wiedergabegerätekontext anhand der durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse neu. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Dieser Datensatz definiert das Fenster für den Wiedergabegerätekontext anhand der durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse neu. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Dieser Datensatz speichert den aktuellen Zustand des Wiedergabegerätekontexts, indem er Daten, die ausgewählte Objekte und Grafikmodi beschreiben\u2014einschließlich Bitmap, Pinsel, Palette, Schriftart, Stift, Bereich, Zeichenmodus und Abbildungsmodus\u2014in einen Stapel gespeicherter Geräte‑Kontexte kopiert. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Dieser Datensatz stellt den Wiedergabegerätekontext auf den angegebenen gespeicherten Zustand wieder her. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Dieser Datensatz definiert eine zweidimensionale lineare Transformation zwischen Welt­raum und Seiten­raum (für weitere Informationen siehe [MSDN-WRLDPGSPC]) für den Wiedergabegerätekontext. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Dieser Datensatz definiert die Welttransformation für den Wiedergabegerätekontext anhand des angegebenen Modus neu. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Dieser Datensatz fügt dem Wiedergabegerätekontext ein Objekt hinzu, das anhand seines Indexes in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) identifiziert wird. |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Dieser Datensatz definiert einen logischen Stift mit dem angegebenen Stil, der Breite und der Farbe. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Dieser Datensatz definiert einen logischen Pinsel zum Füllen von Figuren in Grafikoperationen. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Dieser Datensatz löscht ein Grafikobjekt und entfernt dessen Index aus der EMF‑Objekttabelle. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Dieser Datensatz definiert ein Liniensegment eines Bogens. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Dieser Datensatz definiert eine Ellipse. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Dieser Datensatz definiert ein Rechteck. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Dieser Datensatz definiert ein Rechteck mit abgerundeten Ecken. |
| [EMR_ARC](#EMR-ARC) | Dieser Datensatz definiert einen elliptischen Bogen. |
| [EMR_CHORD](#EMR-CHORD) | Dieser Datensatz definiert eine Sehne (ein Gebiet, das durch die Schnittmenge einer Ellipse und eines Liniensegments begrenzt ist, ein sogenannter Sekante). |
| [EMR_PIE](#EMR-PIE) | Dieser Datensatz definiert einen keilförmigen Abschnitt, begrenzt durch die Schnittmenge einer Ellipse und zweier Radialen. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Dieser Datensatz fügt dem Wiedergabegeräte-Kontext ein LogPalette-Objekt (Abschnitt 2.2.17) hinzu und identifiziert es über seinen Index in der EMF-Objekttabelle. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Dieser Datensatz definiert ein LogPalette-Objekt. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Dieser Datensatz definiert RGB (Rot-Grün-Blau)-Farbwerte in einem Bereich von Einträgen eines LogPalette-Objekts. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Dieser Datensatz erhöht oder verringert die Größe einer logischen Palette. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Dieser Datensatz ordnet Einträge der aktuellen logischen Palette der Systempalette zu. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Dieser Datensatz füllt einen Bereich der Anzeigefläche mit dem aktuellen Pinsel. |
| [EMR_LINETO](#EMR-LINETO) | Dieser Datensatz definiert eine Linie von der aktuellen Position bis zu, aber nicht einschließlich, dem angegebenen Punkt. |
| [EMR_ARCTO](#EMR-ARCTO) | Dieser Datensatz definiert einen elliptischen Bogen. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Dieser Datensatz definiert die Zeichenrichtung, die für Bogen- und Rechteckoperationen verwendet wird. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Dieser Datensatz definiert die Grenze für die Länge von Gehrungsverbindungen im Wiedergabegeräte-Kontext. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Dieser Datensatz öffnet eine Pfadklammer im Wiedergabegeräte-Kontext. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Dieser Datensatz schließt eine Pfadklammer und wählt den durch die Klammer definierten Pfad in den Wiedergabegeräte‑Kontext aus. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Dieser Datensatz schließt eine offene Figur in einem Pfad. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Dieser Datensatz schließt alle offenen Figuren im aktuellen Pfad und füllt das Innere des Pfades mithilfe des aktuellen Pinsels und des Polygonfüllmodus. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfades mit dem aktuellen Stift und füllt das Innere mit dem aktuellen Pinsel. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Dieser Datensatz rendert den angegebenen Pfad mit dem aktuellen Stift. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Dieser Datensatz transformiert jede im Pfad ausgewählte Kurve in den Wiedergabegeräte-Kontext und wandelt jede Kurve in eine Sequenz von Linien um. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Dieser Datensatz definiert den aktuellen Pfad neu als den Bereich, der gemalt würde, wenn der Pfad mit dem aktuell im Wiedergabegeräte-Kontext ausgewählten Stift nachgezogen würde. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Dieser Datensatz definiert den aktuellen Pfad als Clipping‑Region für den Wiedergabegeräte-Kontext und kombiniert die neue Region mit einer vorhandenen Clipping‑Region unter Verwendung des angegebenen Modus. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Dieser Datensatz bricht eine Pfadklammer ab oder verwirft den Pfad aus einer geschlossenen Pfadklammer. |
| [EMR_COMMENT](#EMR-COMMENT) | Dieser Datensatz gibt beliebige private Daten an. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Dieser Datensatz füllt die angegebene Region mit dem angegebenen Pinsel. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Dieser Datensatz zeichnet einen Rand um die angegebene Region mit dem angegebenen Pinsel. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Dieser Datensatz invertiert die Farben in der angegebenen Region. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Dieser Datensatz malt die angegebene Region mit dem aktuell im Wiedergabegeräte-Kontext ausgewählten Pinsel. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Dieser Datensatz kombiniert die angegebene Region mit der aktuellen Clip‑Region unter Verwendung des angegebenen Modus. |
| [EMR_BITBLT](#EMR-BITBLT) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster und mit Anwendung einer Farbmasken‑Bitmap, gemäß angegebenen Vordergrund- und Hintergrund‑Rasteroperationen. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielparallelogramm an, mit Anwendung einer Farbmasken‑Bitmap. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von angegebenen Scanlinien einer Quell‑Bitmap zu einem Zielrechteck an. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Dieser Datensatz definiert eine logische Schriftart, die die angegebenen Merkmale aufweist. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Dieser Datensatz zeichnet eine ASCII‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben. Hinweis: EMR\_EXTTEXTOUTA SOLLTE mit einem EMR\_EXTTEXTOUTW‑Datensatz emuliert werden (Abschnitt 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Dieser Datensatz zeichnet eine Unicode‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Scheitelpunkten besteht, die durch gerade Linien verbunden sind. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen Array verbindet. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven basierend auf der aktuellen Position. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Dieser Datensatz definiert eine oder mehrere gerade Linien basierend auf der aktuellen Position. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Dieser Datensatz definiert eine Reihe geschlossener Polygone. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Dieser Datensatz definiert einen logischen Pinsel mit dem angegebenen Bitmap‑Muster. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Dieser Datensatz definiert einen logischen Pinsel, der das durch das DIB angegebene Muster hat. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Dieser Datensatz definiert einen logischen kosmetischen oder geometrischen Stift, der den angegebenen Stil, die Breite und die Pinselattribute besitzt. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Dieser Datensatz zeichnet eine oder mehrere ASCII‑Textzeichenfolgen mit der aktuellen Schriftart und den Textfarben. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Dieser Datensatz zeichnet eine oder mehrere Unicode‑Textzeichenfolgen mit der aktuellen Schriftart und den Textfarben. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Dieser Datensatz gibt den Modus der Bildfarbverwaltung (ICM) für Grafikoperationen an. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Dieser Datensatz erstellt ein logisches Farbraum‑Objekt aus einem Farbprofil mit einem Namen, der aus ASCII‑Zeichen besteht. |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Dieser Datensatz definiert das aktuelle logische Farbraum‑Objekt für Grafikoperationen. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Dieser Datensatz löscht ein logisches Farbraum‑Objekt. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Dieser Datensatz gibt eine OpenGL‑Funktion an. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Dieser Datensatz gibt eine OpenGL‑Funktion mit einem Begrenzungsrechteck für die Ausgabe an. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Dieser Datensatz gibt das zu verwendende Pixel‑Format für Grafikoperationen an. |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Dieser Datensatz übergibt beliebige Informationen an den Treiber. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Dieser Datensatz übergibt beliebige Informationen an den Treiber. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Dieser Datensatz gibt eine Zeichenkette aus. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Dieser Datensatz zwingt den Schriftarten‑Mapper, Schriftarten anhand ihrer UniversalFontId anstelle ihrer LogFont‑Informationen zuzuordnen. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Dieser Datensatz übergibt beliebige Informationen an den angegebenen benannten Treiber. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Dieser Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mithilfe von Windows Color System (WCS) 1.0-Werten korrigiert werden. |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus ASCII‑Zeichen besteht, für die Grafik­ausgabe. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus Unicode‑Zeichen besteht, für die Grafik­ausgabe. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, einschließlich Alpha‑Transparenzdaten, gemäß einer angegebenen Mischoperation. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Dieser Datensatz gibt die Reihenfolge an, in der Text und Grafiken gezeichnet werden. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, wobei eine angegebene Farbe als transparent behandelt wird, und dehnt die Ausgabe bei Bedarf, um die Abmessungen des Ziels zu passen, oder komprimiert sie. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Dieser Datensatz gibt das Füllen von Rechtecken oder Dreiecken mit Farbverläufen an. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Dieser Datensatz legt die UniversalFontIds verknüpfter Schriftarten fest, die bei der Zeichensuche verwendet werden. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Dieser Datensatz gibt die Menge an zusätzlichem Abstand an, der zu Trennzeichen für Blocksatzzwecke hinzugefügt wird. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Dieser Datensatz gibt an, ob eine Farbangleichung mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem Namen aus Unicode‑Zeichen angegeben ist. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus Unicode‑Zeichen besteht. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Dieser Datensatz definiert den Beginn der Metadatei und gibt ihre Eigenschaften an; ihren Inhalt, einschließlich der Abmessungen des eingebetteten Bildes; die Anzahl der Datensätze in der Metadatei; und die Auflösung des Geräts, auf dem das eingebettete Bild erstellt wurde. Diese Werte ermöglichen es, dass die Metadatei geräteunabhängig ist.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Dieser Datensatz definiert einen oder mehrere Bézier‑Kurven. Kubische Bézier‑Kurven werden anhand angegebener Endpunkte und Kontrollpunkte definiert und mit dem aktuellen Stift gezeichnet.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel und dem Polygon‑Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezeichnet wird.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen Array verbindet.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven basierend auf der aktuellen Position.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Dieser Datensatz definiert einen oder mehrere gerade Linien basierend auf der aktuellen Position. Eine Linie wird von der aktuellen Position zum ersten durch das Feld points angegebenen Punkt mit dem aktuellen Stift gezeichnet. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie zum nächsten durch points angegebenen Punkt gezeichnet.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente. Die Liniensegmente werden mit dem aktuellen Stift gezeichnet. Die durch die Segmente gebildeten Figuren werden nicht gefüllt. Die aktuelle Position wird von diesem Datensatz weder verwendet noch aktualisiert.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel und dem Polygon‑Füllmodus gefüllt. Die durch diesen Datensatz definierten Polygone können sich überschneiden.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Dieser Datensatz definiert die Fensterausdehnung.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Dieser Datensatz definiert den Fensterursprung.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Dieser Datensatz definiert die Viewport‑Ausdehnung.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Dieser Datensatz definiert den Viewport‑Ursprung.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Dieser Datensatz definiert den Ursprung des aktuellen Pinsels.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Dieser Datensatz kennzeichnet das Ende der Metadatei.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Dieser Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Dieser Datensatz gibt Parameter des Prozesses an, bei dem logische Schriften zu physischen Schriften zugeordnet werden, was vom Font‑Mapper durchgeführt wird.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Dieser Datensatz definiert den Abbildungsmodus des Wiedergabegeräte‑Kontexts. Der Abbildungsmodus definiert die Maßeinheit, die verwendet wird, um Seiteneinheiten in Geräteeinheiten umzuwandeln, und legt außerdem die Orientierung der x‑ und y‑Achse des Geräts fest.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Dieser Datensatz definiert den Hintergrund‑Mischmodus des Wiedergabegeräte‑Kontexts. Der Hintergrund‑Mischmodus wird bei Text, schraffierten Pinseln und Stift‑Stilen verwendet, die keine durchgezogenen Linien sind.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Dieser Datensatz definiert den Füllmodus für Polygone.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Dieser Datensatz definiert den binären Raster‑Operations‑Modus.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Dieser Datensatz definiert den Bitmap-Streckmodus.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Dieser Datensatz definiert die Textausrichtung.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Dieser Datensatz definiert die Farbkorrekturwerte für den Wiedergabegerätekontext unter Verwendung der angegebenen Werte.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Dieser Datensatz definiert die aktuelle Textfarbe.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Dieser Datensatz definiert die Hintergrundfarbe.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Dieser Datensatz definiert den Clipping‑Bereich des Wiedergabegerätekontexts anhand der angegebenen Offsets neu.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Dieser Datensatz definiert die Koordinaten der neuen aktuellen Position in logischen Einheiten.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Dieser Datensatz schneidet die aktuelle Clipping‑Region des Wiedergabegeräte‑Kontexts mit der aktuellen Meta‑Region und speichert die kombinierte Region als neue Meta‑Region. Die Clipping‑Region wird auf eine Null‑Region zurückgesetzt.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Dieser Datensatz definiert einen neuen Clipping‑Bereich, der aus dem bestehenden Clipping‑Bereich abzüglich des angegebenen Rechtecks besteht.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Dieser Datensatz definiert einen neuen Clipping‑Bereich aus der Schnittmenge des aktuellen Clipping‑Bereichs und des angegebenen Rechtecks.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Dieser Datensatz definiert den Ansichtsbereich für den Wiedergabegerätekontext anhand der durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse neu.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Dieser Datensatz definiert das Fenster für den Wiedergabegerätekontext anhand der durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse neu.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Dieser Datensatz speichert den aktuellen Zustand des Wiedergabegerätekontexts, indem er Daten, die ausgewählte Objekte und Grafikmodi beschreiben\u2014einschließlich Bitmap, Pinsel, Palette, Schriftart, Stift, Bereich, Zeichenmodus und Abbildungsmodus\u2014in einen Stapel gespeicherter Geräte‑Kontexte kopiert.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Dieser Datensatz stellt den Wiedergabegeräte‑Kontext auf den angegebenen gespeicherten Zustand wieder her. Der Wiedergabegeräte‑Kontext wird wiederhergestellt, indem Zustandsinformationen von einem Stapel gespeicherter Geräte‑Kontexte, die durch frühere EMR\_SAVEDC‑Datensätze (Abschnitt 2.3.11) erstellt wurden, abgepoppt werden.

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Dieser Datensatz definiert eine zweidimensionale lineare Transformation zwischen Welt‑ und Seitenraum (weitere Informationen siehe [MSDN-WRLDPGSPC]) für den Wiedergabegeräte‑Kontext. Diese Transformation kann zum Skalieren, Drehen, Scheren oder Verschieben der Grafik­ausgabe verwendet werden.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Dieser Datensatz definiert die Welttransformation für den Wiedergabegerätekontext anhand des angegebenen Modus neu.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Dieser Datensatz fügt dem Wiedergabegerätekontext ein Objekt hinzu, das anhand seines Indexes in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) identifiziert wird.

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Dieser Datensatz definiert einen logischen Stift, der den angegebenen Stil, die Breite und die Farbe hat. Der Stift kann anschließend in den Wiedergabegeräte‑Kontext ausgewählt und zum Zeichnen von Linien und Kurven verwendet werden.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Dieser Datensatz definiert einen logischen Pinsel zum Füllen von Figuren in Grafikoperationen.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Dieser Datensatz löscht ein Grafikobjekt und räumt dessen Index in der EMF‑Objekttabelle auf. Wenn das gelöschte Objekt im Wiedergabegeräte‑Kontext ausgewählt ist, muss das Standardobjekt für diese Kontext‑Eigenschaft wiederhergestellt werden.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Dieser Datensatz definiert ein Liniensegment eines Bogens. Das Liniensegment wird von der aktuellen Position zum Beginn des Bogens gezeichnet. Der Bogen wird entlang des Umfangs eines Kreises mit dem angegebenen Radius und Zentrum gezeichnet. Die Länge des Bogens wird durch die angegebenen Start‑ und Sweep‑Winkel definiert.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Dieser Datensatz definiert eine Ellipse. Der Mittelpunkt der Ellipse ist der Mittelpunkt des angegebenen Begrenzungsrechtecks. Die Ellipse wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Dieser Datensatz definiert ein Rechteck. Das Rechteck wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Dieser Datensatz definiert ein Rechteck mit abgerundeten Ecken. Das Rechteck wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Dieser Datensatz definiert einen elliptischen Bogen.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Dieser Datensatz definiert eine Sehne (ein Gebiet, das durch die Schnittmenge einer Ellipse und eines Liniensegments, einer Sekante, begrenzt ist). Die Sehne wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Dieser Datensatz definiert ein keilförmiges Segment, das durch die Schnittmenge einer Ellipse und zweier Radien begrenzt ist. Das Segment wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Dieser Datensatz fügt dem Wiedergabegeräte-Kontext ein LogPalette-Objekt (Abschnitt 2.2.17) hinzu und identifiziert es über seinen Index in der EMF-Objekttabelle.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Dieser Datensatz definiert ein LogPalette-Objekt.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Dieser Datensatz definiert RGB (Rot-Grün-Blau)-Farbwerte in einem Bereich von Einträgen eines LogPalette-Objekts.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Dieser Datensatz erhöht oder verringert die Größe einer logischen Palette.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Dieser Datensatz ordnet Einträge der aktuellen logischen Palette der Systempalette zu.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Dieser Datensatz füllt einen Bereich der Anzeigefläche mit dem aktuellen Pinsel.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Dieser Datensatz definiert eine Linie von der aktuellen Position bis (aber nicht einschließlich) dem angegebenen Punkt. Er setzt die aktuelle Position auf den angegebenen Punkt zurück.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Dieser Datensatz definiert einen elliptischen Bogen. Er setzt die aktuelle Position auf den Endpunkt des Bogens zurück.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Dieser Datensatz definiert die Zeichenrichtung, die für Bogen- und Rechteckoperationen verwendet wird.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Dieser Datensatz definiert die Grenze für die Länge von Gehrungsverbindungen im Wiedergabegeräte-Kontext.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Dieser Datensatz öffnet eine Pfadklammer im Wiedergabegeräte-Kontext.

--------------------

Nachdem eine Pfadklammer geöffnet ist, kann eine Anwendung mit der Verarbeitung von Datensätzen beginnen, um die Punkte zu definieren, die im Pfad liegen. Eine Anwendung MUSS eine offene Pfadklammer schließen, indem sie den EMR\_ENDPATH‑Datensatz verarbeitet. Wenn eine Anwendung den EMR\_BEGINPATH‑Datensatz verarbeitet, MÜSSEN alle vorherigen Pfade aus dem Wiedergabegerätekontext verworfen werden.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Dieser Datensatz schließt eine Pfadklammer und wählt den durch die Klammer definierten Pfad in den Wiedergabegeräte‑Kontext aus.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Dieser Datensatz schließt eine offene Figur in einem Pfad.

--------------------

Die Verarbeitung des EMR\_CLOSEFIGURE‑Datensatzes MUSS die Figur schließen, indem eine Linie von der aktuellen Position zum ersten Punkt der Figur gezeichnet wird, und anschließend MUSS sie die Linien mit dem Linienverbindungsstil verbinden. Wenn eine Figur durch Verarbeitung des EMR\_LINETO‑Datensatzes anstelle des EMR\_CLOSEFIGURE‑Datensatzes geschlossen wird, werden Endkappen verwendet, um die Ecke zu erzeugen, anstatt einer Verbindung. EMR\_LINETO ist in Abschnitt 2.3.5.13 angegeben. Der EMR\_CLOSEFIGURE‑Datensatz SOLLTE nur verwendet werden, wenn im Wiedergabegerätekontext eine offene Pfadklammer vorhanden ist. Eine Figur in einem Pfad ist offen, sofern sie nicht ausdrücklich durch Verarbeitung dieses Datensatzes geschlossen wird. Hinweis: Eine Figur kann offen sein, selbst wenn der aktuelle Punkt und der Startpunkt der Figur identisch sind. Nach der Verarbeitung des EMR\_CLOSEFIGURE‑Datensatzes MUSS das Hinzufügen einer Linie oder Kurve zum Pfad eine neue Figur beginnen.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Dieser Datensatz schließt alle offenen Figuren im aktuellen Pfad und füllt das Innere des Pfades mithilfe des aktuellen Pinsels und des Polygonfüllmodus.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfades mit dem aktuellen Stift und füllt das Innere mit dem aktuellen Pinsel.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Dieser Datensatz rendert den angegebenen Pfad mit dem aktuellen Stift.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Dieser Datensatz transformiert jede im Pfad ausgewählte Kurve in den Wiedergabegeräte-Kontext und wandelt jede Kurve in eine Sequenz von Linien um.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Dieser Datensatz definiert den aktuellen Pfad neu als den Bereich, der gemalt würde, wenn der Pfad mit dem aktuell im Wiedergabegeräte-Kontext ausgewählten Stift nachgezogen würde.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Dieser Datensatz definiert den aktuellen Pfad als Clipping‑Region für den Wiedergabegeräte-Kontext und kombiniert die neue Region mit einer vorhandenen Clipping‑Region unter Verwendung des angegebenen Modus.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Dieser Datensatz bricht eine Pfadklammer ab oder verwirft den Pfad aus einer geschlossenen Pfadklammer.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Dieser Datensatz gibt beliebige private Daten an.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Dieser Datensatz füllt die angegebene Region mit dem angegebenen Pinsel.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Dieser Datensatz zeichnet einen Rand um die angegebene Region mit dem angegebenen Pinsel.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Dieser Datensatz invertiert die Farben in der angegebenen Region.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Dieser Datensatz malt die angegebene Region mit dem aktuell im Wiedergabegeräte-Kontext ausgewählten Pinsel.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Dieser Datensatz kombiniert die angegebene Region mit der aktuellen Clip‑Region unter Verwendung des angegebenen Modus.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster und mit Anwendung einer Farbmasken‑Bitmap, gemäß angegebenen Vordergrund- und Hintergrund‑Rasteroperationen.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielparallelogramm an, mit Anwendung einer Farbmasken‑Bitmap.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von angegebenen Scanlinien einer Quell‑Bitmap zu einem Zielrechteck an.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Dieser Datensatz definiert eine logische Schriftart mit den angegebenen Merkmalen. Die Schriftart kann anschließend als aktuelle Schriftart für den Wiedergabegerätekontext ausgewählt werden.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Dieser Datensatz zeichnet eine ASCII‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben. Hinweis: EMR\_EXTTEXTOUTA SOLLTE mit einem EMR\_EXTTEXTOUTW‑Datensatz emuliert werden (Abschnitt 2.3.5.8). Dies erfordert, dass die ASCII‑Textzeichenfolge im EmrText‑Objekt in Unicode‑UTF16‑LE‑Kodierung konvertiert wird.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Dieser Datensatz zeichnet eine Unicode‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven. Die Kurven werden mit dem aktuellen Stift gezeichnet.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel und dem Polygon‑Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezeichnet wird.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen Array verbindet.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Dieser Datensatz definiert eine oder mehrere Bézier‑Kurven basierend auf der aktuellen Position.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Dieser Datensatz definiert eine oder mehrere gerade Linien basierend auf der aktuellen Position. Eine Linie wird von der aktuellen Position zum ersten durch das Feld Points angegebenen Punkt mit dem aktuellen Stift gezeichnet. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie zum nächsten durch Points angegebenen Punkt gezeichnet.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel sowie dem Polygonfüllmodus gefüllt. Die durch diesen Datensatz angegebenen Polygone können sich überlappen.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Dieser Datensatz definiert einen logischen Pinsel mit dem angegebenen Bitmap‑Muster. Das Bitmap kann ein geräteunabhängiges Bitmap (DIB)‑Abschnitts‑Bitmap oder ein geräteabhängiges Bitmap sein.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Dieser Datensatz definiert einen logischen Pinsel, der das durch das DIB angegebene Muster hat.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Dieser Datensatz definiert einen logischen kosmetischen oder geometrischen Stift, der den angegebenen Stil, die Breite und die Pinselattribute besitzt.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Dieser Datensatz zeichnet ein oder mehrere ASCII‑Textzeichenketten mit der aktuellen Schriftart und den Textfarben. Hinweis: EMR\_POLYTEXTOUTA SOLLTE mit einer Reihe von EMR\_EXTTEXTOUTW‑Datensätzen emuliert werden, einer pro Zeichenkette.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Dieser Datensatz zeichnet ein oder mehrere Unicode‑Textzeichenketten mit der aktuellen Schriftart und den Textfarben. Hinweis: EMR\_POLYTEXTOUTW SOLLTE mit einer Reihe von EMR\_EXTTEXTOUTW‑Datensätzen emuliert werden, einer pro Zeichenkette.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Dieser Datensatz gibt den Modus der Bildfarbverwaltung (ICM) für Grafikoperationen an.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Dieser Datensatz erstellt ein logisches Farbraum‑Objekt aus einem Farbprofil mit einem Namen, der aus ASCII‑Zeichen besteht.

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Dieser Datensatz definiert das aktuelle logische Farbraum‑Objekt für Grafikoperationen.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Dieser Datensatz löscht ein logisches Farbraum‑Objekt. Hinweis: Ein EMR\_DELETEOBJECT‑Datensatz SOLLTE anstelle von EMR\_DELETECOLORSPACE verwendet werden, um ein logisches Farbraum‑Objekt zu löschen.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Dieser Datensatz gibt eine OpenGL‑Funktion an.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Dieser Datensatz gibt eine OpenGL‑Funktion mit einem Begrenzungsrechteck für die Ausgabe an.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Dieser Datensatz gibt das zu verwendende Pixel‑Format für Grafikoperationen an.

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Dieser Datensatz übergibt beliebige Informationen an den Treiber. Die Absicht ist, dass die Informationen zu einer Ausführung von Zeichenoperationen führen.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Dieser Datensatz übergibt beliebige Informationen an den Treiber. Die Absicht ist, dass die Informationen nicht zu einer Ausführung von Zeichenoperationen führen.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Dieser Datensatz gibt eine Zeichenkette aus.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Dieser Datensatz zwingt den Schriftarten‑Mapper, Schriftarten anhand ihrer UniversalFontId anstelle ihrer LogFont‑Informationen zuzuordnen.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Dieser Datensatz übergibt beliebige Informationen an den angegebenen benannten Treiber.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Dieser Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mithilfe von Windows Color System (WCS) 1.0-Werten korrigiert werden.

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus ASCII‑Zeichen besteht, für die Grafik­ausgabe.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus Unicode‑Zeichen besteht, für die Grafik­ausgabe.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, einschließlich Alpha‑Transparenzdaten, gemäß einer angegebenen Mischoperation.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Dieser Datensatz gibt die Reihenfolge an, in der Text und Grafiken gezeichnet werden.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck an, wobei eine angegebene Farbe als transparent behandelt wird, und dehnt die Ausgabe bei Bedarf, um die Abmessungen des Ziels zu passen, oder komprimiert sie.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Dieser Datensatz gibt das Füllen von Rechtecken oder Dreiecken mit Farbverläufen an.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Dieser Datensatz legt die UniversalFontIds verknüpfter Schriftarten fest, die bei der Zeichensuche verwendet werden.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Dieser Datensatz gibt die Menge an zusätzlichem Abstand an, der zu Trennzeichen für Blocksatzzwecke hinzugefügt wird.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Dieser Datensatz gibt an, ob eine Farbangleichung mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem Namen aus Unicode‑Zeichen angegeben ist.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus Unicode‑Zeichen besteht.

