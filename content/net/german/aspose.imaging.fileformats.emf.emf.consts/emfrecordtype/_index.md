---
title: EmfRecordType
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die RecordType-Enumeration definiert Werte die EMF-Datensätze eindeutig identifizieren. Diese Werte werden im Typfeld jedes Datensatzes bereitgestellt.
type: docs
weight: 2820
url: /de/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

Die RecordType-Enumeration definiert Werte, die EMF-Datensätze eindeutig identifizieren. Diese Werte werden im Typfeld jedes Datensatzes bereitgestellt.

```csharp
public enum EmfRecordType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| EMR_HEADER | `1` | Dieser Datensatz definiert den Beginn der Metadatei und spezifiziert ihre Eigenschaften; seinen Inhalt, einschließlich der Abmessungen des eingebetteten Bildes; die Anzahl der Datensätze in der Metadatei; und die -Auflösung des Geräts, auf dem das eingebettete Bild erstellt wurde. Diese Werte machen es möglich, dass die Metadatei geräteunabhängig ist. |
| EMR_POLYBEZIER | `2` | Dieser Datensatz definiert eine oder mehrere Bezier-Kurven. Kubische Bezier-Kurven werden mit angegebenen Endpunkten und Kontrollpunkten definiert und mit dem aktuellen Stift gezeichnet. |
| EMR_POLYGON | `3` | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade -Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel und Polygon-Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezogen wird. |
| EMR_POLYLINE | `4` | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen -Array verbindet. |
| EMR_POLYBEZIERTO | `5` | Dieser Datensatz definiert eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position. |
| EMR_POLYLINETO | `6` | Dieser Datensatz definiert eine oder mehrere gerade Linien basierend auf der aktuellen Position. Mit dem aktuellen Stift wird eine Linie von der aktuellen Position zum ersten im Punktefeld angegebenen Punkt gezogen. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie zum nächsten durch Punkte angegebenen Punkt gezeichnet. |
| EMR_POLYPOLYLINE | `7` | Dieser Datensatz definiert mehrere Serien verbundener Liniensegmente. Die Liniensegmente werden mit dem aktuellen Stift gezeichnet. Die durch die Segmente gebildeten Figuren werden nicht gefüllt. T Die aktuelle Position wird von diesem Datensatz weder verwendet noch aktualisiert. |
| EMR_POLYPOLYGON | `8` | Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel- und Polygon-Füllmodus gefüllt. Die durch diesen Datensatz definierten Polygone können sich überlappen. |
| EMR_SETWINDOWEXTEX | `9` | Dieser Datensatz definiert die Fensterausdehnung. |
| EMR_SETWINDOWORGEX | `10` | Dieser Datensatz definiert den Fensterursprung. |
| EMR_SETVIEWPORTEXTEX | `11` | Dieser Datensatz definiert die Ausdehnung des Darstellungsbereichs. |
| EMR_SETVIEWPORTORGEX | `12` | Dieser Datensatz definiert den Ursprung des Ansichtsfensters. |
| EMR_SETBRUSHORGEX | `13` | Dieser Datensatz definiert den Ursprung des aktuellen Pinsels. |
| EMR_EOF | `14` | Dieser Datensatz gibt das Ende der Metadatei an. |
| EMR_SETPIXELV | `15` | Dieser Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten. |
| EMR_SETMAPPERFLAGS | `16` | Dieser Datensatz spezifiziert Parameter für den Prozess des Abgleichs logischer Schriftarten mit physischen Schriftarten, der von der Schriftartzuordnung durchgeführt wird. |
| EMR_SETMAPMODE | `17` | Dieser Datensatz definiert den Abbildungsmodus des Kontexts des Wiedergabegeräts. Der Zuordnungsmodus definiert die Maßeinheit, die zum Umwandeln von Seitenbereichseinheiten in Gerätebereichseinheiten verwendet wird, und definiert auch die Ausrichtung der x- und y-Achse des Geräts. |
| EMR_SETBKMODE | `18` | Dieser Datensatz definiert den Hintergrundmischmodus des Wiedergabegerätekontexts. Der Hintergrundmix -Modus wird mit Text, schraffierten Pinseln und Stiftstilen verwendet, die keine durchgezogenen Linien sind. |
| EMR_SETPOLYFILLMODE | `19` | Dieser Datensatz definiert den Polygon-Füllmodus. |
| EMR_SETROP2 | `20` | Dieser Datensatz definiert den binären Raster-Betriebsmodus. |
| EMR_SETSTRETCHBLTMODE | `21` | Dieser Datensatz definiert den Bitmap-Stretch-Modus. |
| EMR_SETTEXTALIGN | `22` | Dieser Datensatz definiert die Textausrichtung. |
| EMR_SETCOLORADJUSTMENT | `23` | Dieser Datensatz definiert die Farbanpassungswerte für den Kontext des Wiedergabegeräts unter Verwendung der angegebenen Werte. |
| EMR_SETTEXTCOLOR | `24` | Dieser Datensatz definiert die aktuelle Textfarbe. |
| EMR_SETBKCOLOR | `25` | Dieser Datensatz definiert die Hintergrundfarbe. |
| EMR_OFFSETCLIPRGN | `26` | Dieser Datensatz definiert den Clipping-Bereich des Kontexts des Wiedergabegeräts durch die angegebenen Offsets neu. |
| EMR_MOVETOEX | `27` | Dieser Datensatz definiert die Koordinaten der neuen aktuellen Position in logischen Einheiten. |
| EMR_SETMETARGN | `28` | Dieser Datensatz schneidet den aktuellen Clipping-Bereich für den Kontext des Wiedergabegeräts mit dem aktuellen Meta-Bereich und speichert den kombinierten Bereich als neuen Meta-Bereich. Der Clipping-Bereich wird auf einen Null-Bereich zurückgesetzt. |
| EMR_EXCLUDECLIPRECT | `29` | Dieser Datensatz definiert einen neuen Clipping-Bereich, der aus dem vorhandenen Clipping-Bereich minus dem angegebenen Rechteck besteht. |
| EMR_INTERSECTCLIPRECT | `30` | Dieser Datensatz definiert einen neuen Clipping-Bereich aus dem Schnittpunkt des aktuellen Clipping-Bereichs und des angegebenen Rechtecks. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Dieser Datensatz definiert den Darstellungsbereich für den Kontext des Wiedergabegeräts neu, indem er die Verhältnisse verwendet, die durch die angegebenen Multiplikanden und Divisoren gebildet werden. |
| EMR_SCALEWINDOWEXTEX | `32` | Dieser Datensatz definiert das Fenster für den Kontext des Wiedergabegeräts neu, indem er die Verhältnisse verwendet, die durch die angegebenen Multiplikanden und Divisoren gebildet werden. |
| EMR_SAVEDC | `33` | Dieser Datensatz speichert den aktuellen Zustand des Kontexts des Wiedergabegeräts durch Kopieren von Daten , die ausgewählte Objekte und Grafikmodi beschreiben – einschließlich Bitmap, Pinsel, Palette, Schriftart, Stift, Bereich, Zeichenmodus und Abbildungsmodus – in einen Stapel gespeicherter Daten Gerätekontexte. |
| EMR_RESTOREDC | `34` | Dieser Datensatz stellt den Kontext des Wiedergabegeräts im angegebenen gespeicherten Zustand wieder her. Der Kontext des Wiedergabegeräts wird wiederhergestellt, indem Zustandsinformationen aus einem Stapel von gespeicherten Gerätekontexten entnommen werden, die von früheren EMR_SAVEDC-Datensätzen (Abschnitt 2.3.11) erstellt wurden. |
| EMR_SETWORLDTRANSFORM | `35` | Dieser Datensatz definiert eine zweidimensionale lineare Transformation zwischen dem Weltraum und dem -Seitenraum (weitere Informationen finden Sie unter [MSDN-WRLDPGSPC]) für den Kontext des Wiedergabegeräts. Diese Transformation kann verwendet werden, um die Grafikausgabe zu skalieren, zu drehen, zu scheren oder zu übersetzen. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Dieser Datensatz definiert die Welttransformation für den Kontext des Wiedergabegeräts mithilfe des angegebenen Modus neu. |
| EMR_SELECTOBJECT | `37` | Dieser Datensatz fügt dem Kontext des Wiedergabegeräts ein Objekt hinzu und identifiziert es durch seinen -Index in der EMF-Objekttabelle (Abschnitt 3.1.1.1). |
| EMR_CREATEPEN | `38` | Dieser Datensatz definiert einen logischen Stift, der den angegebenen Stil, die Breite und die Farbe hat. Der Stift kann anschließend im Kontext des Wiedergabegeräts ausgewählt und zum Zeichnen von Linien und Kurven verwendet werden. |
| EMR_CREATEBRUSHINDIRECT | `39` | Dieser Datensatz definiert einen logischen Pinsel zum Füllen von Zahlen in Grafikoperationen. |
| EMR_DELETEOBJECT | `40` | Dieser Datensatz löscht ein Grafikobjekt und löscht seinen Index in der EMF-Objekttabelle. Wenn das gelöschte Objekt im Kontext des Wiedergabegeräts ausgewählt wird, MUSS das Standardobjekt für diese Kontexteigenschaft wiederhergestellt werden. |
| EMR_ANGLEARC | `41` | Dieser Datensatz definiert ein Liniensegment eines Bogens. Das Liniensegment wird von der aktuellen Position zum Anfang des Bogens gezeichnet. Der Bogen wird entlang des Umfangs eines Kreises mit gegebenem Radius und Mittelpunkt gezeichnet. Die Länge des Bogens wird durch die gegebenen Start- und Sweep-Winkel definiert. |
| EMR_ELLIPSE | `42` | Dieser Datensatz definiert eine Ellipse. Der Mittelpunkt der Ellipse ist der Mittelpunkt des angegebenen Begrenzungsrechtecks. Die Ellipse wird mit dem aktuellen Stift umrissen und wird mit dem aktuellen Pinsel gefüllt. |
| EMR_RECTANGLE | `43` | Dieser Datensatz definiert ein Rechteck. Das Rechteck wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| EMR_ROUNDRECT | `44` | Dieser Datensatz definiert ein Rechteck mit abgerundeten Ecken. Das Rechteck wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| EMR_ARC | `45` | Dieser Datensatz definiert einen Ellipsenbogen. |
| EMR_CHORD | `46` | Dieser Datensatz definiert eine Sehne (eine Region, die durch den Schnittpunkt einer Ellipse und eines Liniensegments begrenzt wird, die als Sekante bezeichnet wird). Der Akkord wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel ausgefüllt. |
| EMR_PIE | `47` | Dieser Datensatz definiert einen tortenförmigen Keil, der durch den Schnittpunkt einer Ellipse und zwei Radialen begrenzt wird. Der Kreis wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| EMR_SELECTPALETTE | `48` | Dieser Datensatz fügt ein LogPalette-Objekt (Abschnitt 2.2.17) zum Kontext des Wiedergabegeräts hinzu und identifiziert es durch seinen Index in der EMF-Objekttabelle. |
| EMR_CREATEPALETTE | `49` | Dieser Datensatz definiert ein LogPalette-Objekt. |
| EMR_SETPALETTEENTRIES | `50` | Dieser Datensatz definiert RGB-Farbwerte (Rot-Grün-Blau) in einem Bereich von Einträgen in einem LogPalette-Objekt. |
| EMR_RESIZEPALETTE | `51` | Dieser Datensatz erhöht oder verringert die Größe einer logischen Palette. |
| EMR_REALIZEPALETTE | `52` | Dieser Datensatz ordnet Einträge aus der aktuellen logischen Palette der Systempalette zu. |
| EMR_EXTFLOODFILL | `53` | Dieser Datensatz füllt einen Bereich der Anzeigeoberfläche mit dem aktuellen Pinsel. |
| EMR_LINETO | `54` | Dieser Datensatz definiert eine Linie von der aktuellen Position bis zu, aber nicht einschließlich, dem angegebenen Punkt. Es setzt die aktuelle Position auf den angegebenen Punkt zurück. |
| EMR_ARCTO | `55` | Dieser Datensatz definiert einen Ellipsenbogen. Es setzt die aktuelle Position auf den Endpunkt des Bogens zurück. |
| EMR_POLYDRAW | `56` | Dieser Datensatz definiert eine Reihe von Liniensegmenten und Bezier-Kurven. |
| EMR_SETARCDIRECTION | `57` | Dieser Datensatz definiert die zu verwendende Zeichenrichtung für Bogen- und Rechteckoperationen . |
| EMR_SETMITERLIMIT | `58` | Dieser Datensatz definiert die Grenze für die Länge von Gehrungsverbindungen für den Wiedergabe- -Gerätekontext. |
| EMR_BEGINPATH | `59` | Dieser Datensatz öffnet eine Pfadklammer im Kontext des Wiedergabegeräts. |
| EMR_ENDPATH | `60` | Dieser Datensatz schließt eine Pfadklammer und wählt den durch die Klammer definierten Pfad in den Kontext des Wiedergabegeräts. |
| EMR_CLOSEFIGURE | `61` | Dieser Datensatz schließt eine offene Figur in einem Pfad. |
| EMR_FILLPATH | `62` | Dieser Datensatz schließt alle offenen Figuren im aktuellen Pfad und füllt das Innere des Pfads unter Verwendung des aktuellen Pinsel- und Polygon-Füllmodus. |
| EMR_STROKEANDFILLPATH | `63` | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, streicht den Umriss des Pfads mit dem aktuellen Stift um und füllt sein Inneres mit dem aktuellen Pinsel aus. |
| EMR_STROKEPATH | `64` | Dieser Datensatz gibt den angegebenen Pfad mit dem aktuellen Stift wieder. |
| EMR_FLATTENPATH | `65` | Dieser Datensatz wandelt jede Kurve im ausgewählten Pfad in den -Kontext des Wiedergabegeräts um und verwandelt jede Kurve in eine Folge von Linien. |
| EMR_WIDENPATH | `66` | Dieser Datensatz definiert den aktuellen Pfad neu als den Bereich, der gemalt würde, wenn der Pfad mit dem aktuell im Kontext des Wiedergabegeräts ausgewählten Stift gestrichen würde. |
| EMR_SELECTCLIPPATH | `67` | Dieser Datensatz definiert den aktuellen Pfad als Clipping-Region für den Kontext des Wiedergabegeräts und kombiniert die neue Region mit einer beliebigen vorhandenen Clipping-Region unter Verwendung des angegebenen Modus. |
| EMR_ABORTPATH | `68` | Dieser Datensatz bricht eine Pfadklammer ab oder verwirft den Pfad aus einer geschlossenen Pfadklammer. |
| EMR_COMMENT | `70` | Dieser Datensatz enthält beliebige private Daten. |
| EMR_FILLRGN | `71` | Dieser Datensatz füllt den angegebenen Bereich mithilfe des angegebenen Pinsels. |
| EMR_FRAMERGN | `72` | Dieser Datensatz zeichnet mit dem angegebenen Pinsel einen Rahmen um den angegebenen Bereich. |
| EMR_INVERTRGN | `73` | Dieser Datensatz invertiert die Farben in der angegebenen Region. |
| EMR_PAINTRGN | `74` | Dieser Datensatz malt den angegebenen Bereich mithilfe des aktuell ausgewählten Pinsels in den Kontext des Wiedergabegeräts. |
| EMR_EXTSELECTCLIPRGN | `75` | Dieser Datensatz kombiniert die angegebene Region mit der aktuellen Clip-Region unter Verwendung des angegebenen Modus. |
| EMR_BITBLT | `76` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel -Rechteck, optional in Kombination mit einem Pinselmuster, gemäß einer spezifizierten Rasteroperation. |
| EMR_STRETCHBLT | `77` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel -Rechteck, optional in Kombination mit einem Pinselmuster, gemäß einer spezifizierten raster -Operation, wobei die Ausgabe gestreckt oder gestaucht wird, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich. |
| EMR_MASKBLT | `78` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel -Rechteck, optional in Kombination mit einem Pinselmuster und mit der Anwendung einer -Farbmasken-Bitmap, gemäß spezifizierten Vordergrund- und Hintergrund-Rasteroperationen. |
| EMR_PLGBLT | `79` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Parallelogramm unter Anwendung einer Farbmasken-Bitmap. |
| EMR_SETDIBITSTODEVICE | `80` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von spezifizierten Abtastzeilen einer Quell Bitmap zu einem Zielrechteck. |
| EMR_STRETCHDIBITS | `81` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Rechteck, optional in Kombination mit einem Pinselmuster, gemäß einer spezifizierten Rasteroperation, dehnt oder komprimiert die Ausgabe, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Dieser Datensatz definiert eine logische Schriftart mit den angegebenen Eigenschaften. Die Schriftart kann anschließend als aktuelle Schriftart für den Kontext des Wiedergabegeräts ausgewählt werden. |
| EMR_EXTTEXTOUTA | `83` | Dieser Datensatz zeichnet eine ASCII-Textzeichenfolge unter Verwendung der aktuellen Schriftart und Textfarben. Hinweis EMR_EXTTEXTOUTA SOLLTE mit einem EMR_EXTTEXTOUTW-Datensatz emuliert werden (Abschnitt 2.3.5.8). Dazu muss die ASCII-Textzeichenfolge im EmrText-Objekt in die Unicode-UTF16-LE-Codierung konvertiert werden. |
| EMR_EXTTEXTOUTW | `84` | Dieser Datensatz zeichnet eine Unicode-Textzeichenfolge unter Verwendung der aktuellen Schriftart und Textfarben. |
| EMR_POLYBEZIER16 | `85` | Dieser Datensatz definiert eine oder mehrere Bezier-Kurven. Die Kurven werden mit dem aktuellen Stift gezeichnet. |
| EMR_POLYGON16 | `86` | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel- und Polygon -Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezogen wird. |
| EMR_POLYLINE16 | `87` | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem er die Punkte im angegebenen Array verbindet. |
| EMR_POLYBEZIERTO16 | `88` | Dieser Datensatz definiert eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position. |
| EMR_POLYLINETO16 | `89` | Dieser Datensatz definiert eine oder mehrere gerade Linien basierend auf der aktuellen Position. Mit dem aktuellen Stift wird eine Linie von der aktuellen Position bis zum ersten im Feld Punkte angegebenen Punkt gezogen. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie bis zum nächsten Punkt gezeichnet, der durch Points. angegeben wird. |
| EMR_POLYPOLYLINE16 | `90` | Dieser Datensatz definiert mehrere Serien verbundener Liniensegmente. |
| EMR_POLYPOLYGON16 | `91` | Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel- und Polygon-Füllmodus gefüllt. Die durch diesen Datensatz angegebenen Polygone können sich überlappen. |
| EMR_POLYDRAW16 | `92` | Dieser Datensatz definiert eine Reihe von Liniensegmenten und Bezier-Kurven. |
| EMR_CREATEMONOBRUSH | `93` | Dieser Datensatz definiert einen logischen Pinsel mit dem angegebenen Bitmap-Muster. Die Bitmap kann eine geräteunabhängige Bitmap (DIB)-Abschnittsbitmap oder eine geräteabhängige Bitmap sein. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Dieser Datensatz definiert einen logischen Pinsel, der das von der DIB angegebene Muster hat. |
| EMR_EXTCREATEPEN | `95` | Dieser Datensatz definiert einen logischen kosmetischen oder geometrischen Stift mit den angegebenen Stil-, Breiten- und Pinselattributen. |
| EMR_POLYTEXTOUTA | `96` | Dieser Datensatz zeichnet eine oder mehrere ASCII-Textzeichenfolgen unter Verwendung der aktuellen Schriftart und Textfarben. Hinweis EMR_POLYTEXTOUTA SOLLTE mit einer Reihe von EMR_EXTTEXTOUTW-Datensätzen emuliert werden, einer pro Zeichenfolge |
| EMR_POLYTEXTOUTW | `97` | Dieser Datensatz zeichnet eine oder mehrere Unicode-Textzeichenfolgen unter Verwendung der aktuellen Schriftart und Textfarben. Hinweis EMR_POLYTEXTOUTW SOLLTE mit einer Reihe von EMR_EXTTEXTOUTW-Datensätzen emuliert werden, einer pro Zeichenfolge |
| EMR_SETICMMODE | `98` | Dieser Datensatz gibt den Modus des Image Color Management (ICM) für Grafikoperationen an. |
| EMR_CREATECOLORSPACE | `99` | Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen bestehend aus ASCII-Zeichen |
| EMR_SETCOLORSPACE | `100` | Dieser Datensatz definiert das aktuelle logische Farbraumobjekt für Grafikoperationen. |
| EMR_DELETECOLORSPACE | `101` | Dieser Datensatz löscht ein logisches Farbraumobjekt. Hinweis Ein EMR_DELETEOBJECT-Datensatz SOLLTE anstelle von EMR_DELETECOLORSPACE verwendet werden, um ein logisches Farbraumobjekt zu löschen |
| EMR_GLSRECORD | `102` | Dieser Datensatz gibt eine OpenGL-Funktion an. |
| EMR_GLSBOUNDEDRECORD | `103` | Dieser Datensatz spezifiziert eine OpenGL-Funktion mit einem Begrenzungsrechteck für die Ausgabe. |
| EMR_PIXELFORMAT | `104` | Dieser Datensatz gibt das für Grafikoperationen zu verwendende Pixelformat an |
| EMR_DRAWESCAPE | `105` | Dieser Datensatz übergibt willkürliche Informationen an den Treiber. Die Absicht ist, dass die Information dazu führt, dass die Zeichnung fertig ist. |
| EMR_EXTESCAPE | `106` | Dieser Datensatz übergibt willkürliche Informationen an den Treiber. Die Absicht ist, dass die Information nicht dazu führt, dass das Zeichnen erfolgt. |
| EMR_SMALLTEXTOUT | `108` | Dieser Datensatz gibt einen String aus. |
| EMR_FORCEUFIMAPPING | `109` | Dieser Datensatz zwingt den Font-Mapper, Schriftarten basierend auf ihrer UniversalFontId in Präferenz mit ihren LogFont-Informationen abzugleichen. |
| EMR_NAMEDESCAPE | `110` | Dieser Datensatz übergibt beliebige Informationen an den angegebenen benannten Treiber. |
| EMR_COLORCORRECTPALETTE | `111` | Dieser Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mit Windows Color System (WCS) 1.0 values korrigiert werden. |
| EMR_SETICMPROFILEA | `112` | Dieser Datensatz spezifiziert ein Farbprofil in einer Datei mit einem aus ASCII-Zeichen bestehenden Namen, für die Grafikausgabe. |
| EMR_SETICMPROFILEW | `113` | Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus Unicode-Zeichen besteht, für die Grafikausgabe |
| EMR_ALPHABLEND | `114` | Dieser Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Zielrechteck, einschließlich Alpha-Transparenzdaten, entsprechend einer spezifizierten Mischoperation. |
| EMR_SETLAYOUT | `115` | Dieser Datensatz gibt die Reihenfolge an, in der Text und Grafiken gezeichnet werden |
| EMR_TRANSPARENTBLT | `116` | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quellbitmap zu einem Zielrechteck an, behandelt eine bestimmte Farbe als transparent, dehnt oder komprimiert die Ausgabe, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich |
| EMR_GRADIENTFILL | `118` | Dieser Datensatz spezifiziert das Füllen von Rechtecken oder Dreiecken mit Farbverläufen von color |
| EMR_SETLINKEDUFIS | `119` | Dieser Datensatz legt die UniversalFontIds der verknüpften Schriftarten fest, die während der Zeichensuche verwendet werden sollen. |
| EMR_SETTEXTJUSTIFICATION | `120` | Dieser Datensatz gibt die Menge an zusätzlichem Leerzeichen an, das den Umbruchzeichen für Begründungszwecke hinzugefügt werden soll. |
| EMR_COLORMATCHTOTARGETW | `121` | Dieser Datensatz gibt an, ob ein Farbabgleich mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem aus Unicode-Zeichen bestehenden Namen angegeben ist. |
| EMR_CREATECOLORSPACEW | `122` | Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem Namen, der aus Unicode-Zeichen besteht |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
