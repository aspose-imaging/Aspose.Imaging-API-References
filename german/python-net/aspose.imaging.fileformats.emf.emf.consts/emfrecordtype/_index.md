---
title: "EmfRecordType Aufzählung"
type: docs
weight: 290
url: /de/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

Die RecordType‑Aufzählung definiert Werte, die EMF‑Datensätze eindeutig identifizieren.<br/>            Diese Werte werden im Feld Type jedes Datensatzes bereitgestellt.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| EMR_ABORTPATH | Dieser Datensatz bricht eine Pfadklammer ab oder verwirft den Pfad aus einer geschlossenen Pfadklammer. |
| EMR_ALPHABLEND | Dieser Datensatz spezifiziert einen Blocktransfer von Pixeln von einer Quell‑Bitmap zu einem Zielrechteck,<br/>             einschließlich Alpha‑Transparenzdaten, gemäß einer angegebenen Mischoperation. |
| EMR_ANGLEARC | Dieser Datensatz definiert ein Liniensegment eines Bogens. Das Liniensegment wird vom <br/>            aktuellen Punkt zum Beginn des Bogens gezeichnet. Der Bogen wird entlang des Umfangs <br/>            eines Kreises mit dem angegebenen Radius und Zentrum gezeichnet. Die Länge des Bogens wird durch <br/>            die angegebenen Start‑ und Sweep‑Winkel definiert. |
| EMR_ARC | Dieser Datensatz definiert einen elliptischen Bogen. |
| EMR_ARCTO | Dieser Datensatz definiert einen elliptischen Bogen. Er setzt die aktuelle Position auf den <br/>            Endpunkt des Bogens zurück. |
| EMR_BEGINPATH | Dieser Datensatz öffnet eine Pfadklammer im Wiedergabegeräte‑Kontext. |
| EMR_BITBLT | Dieser Datensatz spezifiziert einen Blocktransfer von Pixeln von einer Quell‑Bitmap zu einem Ziel<br/>             Rechteck, optional in Kombination mit einem Pinsel‑Muster, gemäß einer angegebenen Rasteroperation. |
| EMR_CHORD | Dieser Datensatz definiert eine Sehne (ein Gebiet, begrenzt durch die Schnittmenge einer Ellipse <br/>            und eines Liniensegments, genannt Sekante). Die Sehne wird mit dem aktuellen <br/>            Stift umrandet und mit dem aktuellen Pinsel gefüllt. |
| EMR_CLOSEFIGURE | Dieser Datensatz schließt eine offene Figur in einem Pfad. |
| EMR_COLORCORRECTPALETTE | Dieser Datensatz gibt an, wie die Einträge eines logischen Palettenobjekts mithilfe des Windows <br/>            Color System (WCS) 1.0 korrigiert werden. |
| EMR_COLORMATCHTOTARGETW | Dieser Datensatz gibt an, ob eine Farbanpassung mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem Namen aus Unicode‑Zeichen angegeben ist. |
| EMR_COMMENT | Dieser Datensatz gibt beliebige private Daten an. |
| EMR_CREATEBRUSHINDIRECT | Dieser Datensatz definiert einen logischen Pinsel zum Ausfüllen von Figuren in Grafikoperationen. |
| EMR_CREATECOLORSPACE | Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil, dessen Name aus ASCII‑Zeichen besteht |
| EMR_CREATECOLORSPACEW | Dieser Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil, dessen Name aus Unicode‑Zeichen besteht |
| EMR_CREATEDIBPATTERNBRUSHPT | Dieser Datensatz definiert einen logischen Pinsel, dessen Muster durch das DIB angegeben ist. |
| EMR_CREATEMONOBRUSH | Dieser Datensatz definiert einen logischen Pinsel mit dem angegebenen Bitmap‑Muster. Das Bitmap kann<br/>             ein geräteunabhängiges Bitmap (DIB) Abschnitts‑Bitmap sein oder ein geräteabhängiges Bitmap. |
| EMR_CREATEPALETTE | Dieser Datensatz definiert ein LogPalette‑Objekt. |
| EMR_CREATEPEN | Dieser Datensatz definiert einen logischen Stift, der den angegebenen Stil, die Breite und die Farbe hat. <br/>            Der Stift kann anschließend in den Wiedergabegeräte‑Kontext ausgewählt und zum Zeichnen von Linien und Kurven verwendet werden. |
| EMR_DELETECOLORSPACE | Dieser Datensatz löscht ein logisches Farbraumobjekt. Hinweis: Ein EMR_DELETEOBJECT‑Datensatz SOLLTE <br/>            anstelle von EMR_DELETECOLORSPACE verwendet werden, um ein logisches Farbraumobjekt zu löschen |
| EMR_DELETEOBJECT | Dieser Datensatz löscht ein Grafikobjekt und entfernt dessen Index in der EMF‑Objekttabelle. <br/>            Wenn das gelöschte Objekt im Wiedergabegeräte‑Kontext ausgewählt ist, MUSS das Standardobjekt <br/>            für diese Kontext‑Eigenschaft wiederhergestellt werden. |
| EMR_DRAWESCAPE | Dieser Datensatz übergibt beliebige Informationen an den Treiber. Die Absicht ist, dass die Informationen <br/>            zu einer Ausführung von Zeichenoperationen führen. |
| EMR_ELLIPSE | Dieser Datensatz definiert eine Ellipse. Der Mittelpunkt der Ellipse ist der Mittelpunkt des <br/>            angegebenen Begrenzungsrechtecks. Die Ellipse wird mit dem aktuellen Stift umrandet und <br/>            mit dem aktuellen Pinsel gefüllt. |
| EMR_ENDPATH | Dieser Datensatz schließt eine Pfadklammer und wählt den durch die Klammer definierten Pfad <br/>            in den Wiedergabegerätekontext aus. |
| EMR_EOF | Dieser Datensatz zeigt das Ende der Metadatei an. |
| EMR_EXCLUDECLIPRECT | Dieser Datensatz definiert einen neuen Clipping‑Bereich, der aus dem bestehenden Clipping‑Bereich <br/>            minus dem angegebenen Rechteck besteht. |
| EMR_EXTCREATEFONTINDIRECTW | Dieser Datensatz definiert eine logische Schriftart mit den angegebenen Merkmalen. Die Schriftart <br/>            kann anschließend als aktuelle Schriftart für den Wiedergabegerätekontext ausgewählt werden. |
| EMR_EXTCREATEPEN | Dieser Datensatz definiert einen logischen kosmetischen oder geometrischen Stift mit dem angegebenen Stil, <br/>            der Breite und den Pinsel‑Attributen. |
| EMR_EXTESCAPE | Dieser Datensatz übergibt beliebige Informationen an den Treiber. Die Absicht ist, dass die Informationen <br/>            nicht zu einer Zeichnung führen. |
| EMR_EXTFLOODFILL | Dieser Datensatz füllt einen Bereich der Anzeigefläche mit dem aktuellen Pinsel. |
| EMR_EXTSELECTCLIPRGN | Dieser Datensatz kombiniert den angegebenen Bereich mit dem aktuellen Clip‑Bereich unter Verwendung des <br/>            angegebenen Modus. |
| EMR_EXTTEXTOUTA | Dieser Datensatz zeichnet eine ASCII‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben. Hinweis <br/>            EMR_EXTTEXTOUTA SOLLTE mit einem EMR_EXTTEXTOUTW‑Datensatz (Abschnitt 2.3.5.8) emuliert werden.  <br/>            Dazu muss die ASCII‑Textzeichenfolge im EmrText‑Objekt in Unicode‑UTF16‑LE‑Kodierung konvertiert werden. |
| EMR_EXTTEXTOUTW | Dieser Datensatz zeichnet eine Unicode‑Textzeichenfolge mit der aktuellen Schriftart und den Textfarben. |
| EMR_FILLPATH | Dieser Datensatz schließt alle offenen Figuren im aktuellen Pfad und füllt das Innere des Pfades <br/>            mit dem aktuellen Pinsel und dem Polygon‑Füllmodus. |
| EMR_FILLRGN | Dieser Datensatz füllt den angegebenen Bereich mit dem angegebenen Pinsel. |
| EMR_FLATTENPATH | Dieser Datensatz transformiert jede Kurve im Pfad, die ausgewählt ist, in den Wiedergabegeräte-<br/> Kontext, wobei jede Kurve in eine Sequenz von Linien umgewandelt wird. |
| EMR_FORCEUFIMAPPING | Dieser Datensatz zwingt den Schriftartenzuordner, Schriftarten anhand ihrer UniversalFontId <br/> anstelle ihrer LogFont-Informationen abzugleichen. |
| EMR_FRAMERGN | Dieser Datensatz zeichnet einen Rahmen um die angegebene Region mit dem angegebenen Pinsel. |
| EMR_GLSBOUNDEDRECORD | Dieser Datensatz gibt eine OpenGL-Funktion mit einem Begrenzungsrechteck für die Ausgabe an. |
| EMR_GLSRECORD | Dieser Datensatz gibt eine OpenGL-Funktion an. |
| EMR_GRADIENTFILL | Dieser Datensatz gibt das Füllen von Rechtecken oder Dreiecken mit Farbverläufen an. |
| EMR_HEADER | Dieser Datensatz definiert den Beginn der Metadatei und gibt ihre Eigenschaften an; ihren Inhalt, <br/> einschließlich der Abmessungen des eingebetteten Bildes; die Anzahl der Datensätze in der Metadatei; und die <br/> Auflösung des Geräts, auf dem das eingebettete Bild erstellt wurde. Diese Werte ermöglichen es, dass die Metadatei geräteunabhängig ist. |
| EMR_INTERSECTCLIPRECT | Dieser Datensatz definiert eine neue Clipping-Region aus der Schnittmenge der aktuellen Clipping-<br/> Region und des angegebenen Rechtecks. |
| EMR_INVERTRGN | Dieser Datensatz invertiert die Farben in der angegebenen Region. |
| EMR_LINETO | Dieser Datensatz definiert eine Linie von der aktuellen Position bis (aber nicht einschließlich) <br/> des angegebenen Punktes. Er setzt die aktuelle Position auf den angegebenen Punkt zurück. |
| EMR_MASKBLT | Dieser Datensatz gibt einen Blocktransfer von Pixeln von einer Quell-Bitmap zu einem Ziel-<br/> Rechteck an, optional in Kombination mit einem Pinselmuster und mit Anwendung einer <br/> Farbmasken-Bitmap, gemäß den angegebenen Vordergrund- und Hintergrund-Rasteroperationen. |
| EMR_MODIFYWORLDTRANSFORM | Dieser Datensatz definiert die Welttransformation für den Wiedergabegeräte-Kontext neu, indem er den angegebenen Modus verwendet. |
| EMR_MOVETOEX | Dieser Datensatz definiert die Koordinaten der neuen aktuellen Position in logischen Einheiten. |
| EMR_NAMEDESCAPE | Dieser Datensatz übergibt beliebige Informationen an den angegebenen benannten Treiber. |
| EMR_OFFSETCLIPRGN | Dieser Datensatz definiert die Clipping-Region des Wiedergabegerätekontexts anhand der angegebenen Offsets neu. |
| EMR_PAINTRGN | Dieser Datensatz malt die angegebene Region, indem er den aktuell in <br/>            den Wiedergabegerätekontext ausgewählten Pinsel verwendet. |
| EMR_PIE | Dieser Datensatz definiert ein keilförmiges Segment, das durch die Schnittmenge einer Ellipse <br/>            und zweier Radien begrenzt wird. Das Segment wird mit dem aktuellen Stift umrandet und mit dem <br/>            aktuellen Pinsel gefüllt. |
| EMR_PIXELFORMAT | Dieser Datensatz gibt das zu verwendende Pixelformat für Grafikoperationen an |
| EMR_PLGBLT | Dieser Datensatz spezifiziert einen Blocktransfer von Pixeln von einer Quell-Bitmap zu einem Ziel-<br/>            Parallelogramm, wobei eine Farbmasken-Bitmap angewendet wird. |
| EMR_POLYBEZIER | Dieser Datensatz definiert eine oder mehrere Bézierkurven. Kubische Bézierkurven werden mit<br/>            angegebenen Endpunkten und Kontrollpunkten definiert und mit dem aktuellen Stift gezeichnet. |
| EMR_POLYBEZIER16 | Dieser Datensatz definiert eine oder mehrere Bézierkurven. Die Kurven werden mit dem aktuellen Stift gezeichnet. |
| EMR_POLYBEZIERTO | Dieser Datensatz definiert eine oder mehrere Bézierkurven basierend auf der aktuellen Position. |
| EMR_POLYBEZIERTO16 | Dieser Datensatz definiert eine oder mehrere Bézierkurven, die auf der aktuellen Position basieren. |
| EMR_POLYDRAW | Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven. |
| EMR_POLYDRAW16 | Dieser Datensatz definiert eine Menge von Liniensegmenten und Bézierkurven. |
| EMR_POLYGON | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade <br/>            Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel <br/>            und dem Polygonfüllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezeichnet wird. |
| EMR_POLYGON16 | Dieser Datensatz definiert ein Polygon, das aus zwei oder mehr Eckpunkten besteht, die durch gerade Linien verbunden sind. <br/>            Das Polygon wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel und dem Polygon<br/>             Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezeichnet wird. |
| EMR_POLYLINE | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem die Punkte im angegebenen <br/>            Array verbunden werden. |
| EMR_POLYLINE16 | Dieser Datensatz definiert eine Reihe von Liniensegmenten, indem die Punkte im angegebenen Array verbunden werden. |
| EMR_POLYLINETO | Dieser Datensatz definiert eine oder mehrere gerade Linien, basierend auf der aktuellen Position. <br/>            Eine Linie wird von der aktuellen Position zum ersten Punkt, der im Feld points angegeben ist, <br/>            mit dem aktuellen Stift gezeichnet. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie zum nächsten im Feld points angegebenen Punkt gezeichnet. |
| EMR_POLYLINETO16 | Dieser Datensatz definiert eine oder mehrere gerade Linien, basierend auf der aktuellen Position.<br/>             Eine Linie wird von der aktuellen Position zum ersten Punkt, der im Feld Points angegeben ist, <br/>            mit dem aktuellen Stift gezeichnet. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie zum nächsten im Feld Points angegebenen Punkt gezeichnet. |
| EMR_POLYPOLYGON | Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem <br/>            aktuellen Stift umrandet und mit dem aktuellen Pinsel und dem Polygonfüllmodus gefüllt. Die durch diesen Datensatz definierten Polygone können überlappen. |
| EMR_POLYPOLYGON16 | Dieser Datensatz definiert eine Reihe geschlossener Polygone. Jedes Polygon wird mit dem <br/>            aktuellen Stift umrandet und mit dem aktuellen Pinsel und dem Polygonfüllmodus gefüllt. Die durch diesen Datensatz <br/>            angegebenen Polygone können überlappen. |
| EMR_POLYPOLYLINE | Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente. Die Liniensegmente werden <br/>            mit dem aktuellen Stift gezeichnet. Die durch die Segmente gebildeten Figuren werden nicht gefüllt. D<br/>            ie aktuelle Position wird von diesem Datensatz weder verwendet noch aktualisiert. |
| EMR_POLYPOLYLINE16 | Dieser Datensatz definiert mehrere Reihen verbundener Liniensegmente. |
| EMR_POLYTEXTOUTA | Dieser Datensatz zeichnet ein oder mehrere ASCII-Textzeichenketten mit der aktuellen Schriftart und den Textfarben.<br/>             Hinweis: EMR_POLYTEXTOUTA SOLLTE mit einer Reihe von EMR_EXTTEXTOUTW-Datensätzen emuliert werden, einer pro Zeichenkette |
| EMR_POLYTEXTOUTW | Dieser Datensatz zeichnet ein oder mehrere Unicode-Textzeichenketten mit der aktuellen Schriftart und den Textfarben.<br/>            Hinweis: EMR_POLYTEXTOUTW SOLLTE mit einer Reihe von EMR_EXTTEXTOUTW-Datensätzen emuliert werden, einer pro Zeichenkette |
| EMR_REALIZEPALETTE | Dieser Datensatz ordnet Einträge der aktuellen logischen Palette der Systempalette zu. |
| EMR_RECTANGLE | Dieser Datensatz definiert ein Rechteck. Das Rechteck wird umrandet, indem der aktuelle <br/>            Stift verwendet wird, und gefüllt, indem der aktuelle Pinsel verwendet wird. |
| EMR_RESIZEPALETTE | Dieser Datensatz vergrößert oder verkleinert die Größe einer logischen Palette. |
| EMR_RESTOREDC | Dieser Datensatz stellt den Wiedergabegerätekontext auf den angegebenen gespeicherten Zustand wieder her. <br/>            Der Wiedergabegerätekontext wird wiederhergestellt, indem Zustandsinformationen von einem Stapel von <br/>            gespeicherten Gerätekontexten, die durch frühere EMR_SAVEDC (Abschnitt 2.3.11) Datensätze erstellt wurden, entfernt werden. |
| EMR_ROUNDRECT | Dieser Datensatz definiert ein Rechteck mit abgerundeten Ecken. Das Rechteck wird umrandet <br/>            indem der aktuelle Stift verwendet wird, und gefüllt indem der aktuelle Pinsel verwendet wird. |
| EMR_SAVEDC | Dieser Datensatz speichert den aktuellen Zustand des Wiedergabegerätekontexts, indem Daten <br/>            kopiert werden, die ausgewählte Objekte und Grafikmodi beschreiben – einschließlich Bitmap, Pinsel, Palette, <br/>            Schriftart, Stift, Region, Zeichenmodus und Abbildungsmodus – zu einem Stapel gespeicherter Gerätekontexte. |
| EMR_SCALEVIEWPORTEXTEX | Dieser Datensatz definiert den Ansichtsbereich für den Wiedergabegerätekontext neu, indem die Verhältnisse <br/>            verwendet werden, die durch die angegebenen Multiplikatoren und Divisoren gebildet werden. |
| EMR_SCALEWINDOWEXTEX | Dieser Datensatz definiert das Fenster für den Wiedergabegerätekontext neu, indem die Verhältnisse verwendet werden, die durch die angegebenen Multiplikatoren und Divisoren gebildet werden. |
| EMR_SELECTCLIPPATH | Dieser Datensatz definiert den aktuellen Pfad als Clipping‑Region für den Wiedergabegeräte<br/>            kontext und kombiniert die neue Region mit einer vorhandenen Clipping‑Region unter Verwendung des angegebenen Modus. |
| EMR_SELECTOBJECT | Dieser Datensatz fügt dem Wiedergabegerätekontext ein Objekt hinzu, das über seinen <br/>            Index in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) identifiziert wird. |
| EMR_SELECTPALETTE | Dieser Datensatz fügt dem Wiedergabegerätekontext ein LogPalette‑Objekt (Abschnitt 2.2.17) hinzu, das über seinen Index in der EMF‑Objekttabelle identifiziert wird. |
| EMR_SETARCDIRECTION | Dieser Datensatz definiert die Zeichenrichtung, die für Bogen‑ und Rechteck<br/>             Operationen verwendet wird. |
| EMR_SETBKCOLOR | Dieser Datensatz definiert die Hintergrundfarbe. |
| EMR_SETBKMODE | Dieser Datensatz definiert den Hintergrund‑Mischmodus des Wiedergabegeräte‑Kontexts. Der Hintergrund‑Mischmodus<br/>             wird mit Text, schraffierten Pinseln und Stift‑Stilen verwendet, die keine durchgezogenen Linien sind. |
| EMR_SETBRUSHORGEX | Dieser Datensatz definiert den Ursprung des aktuellen Pinsels. |
| EMR_SETCOLORADJUSTMENT | Dieser Datensatz definiert die Farbkorrekturwerte für den Wiedergabegeräte‑Kontext unter Verwendung der angegebenen Werte. |
| EMR_SETCOLORSPACE | Dieser Datensatz definiert das aktuelle logische Farbraumobjekt für Grafikoperationen. |
| EMR_SETDIBITSTODEVICE | Dieser Datensatz gibt eine Blockübertragung von Pixeln von angegebenen Scan‑Zeilen einer Quell‑Bitmap<br/>             zu einem Zielrechteck an. |
| EMR_SETICMMODE | Dieser Datensatz gibt den Modus der Bildfarbverwaltung (ICM) für Grafikoperationen an. |
| EMR_SETICMPROFILEA | Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus ASCII‑Zeichen besteht,<br/>             für die Grafik­ausgabe. |
| EMR_SETICMPROFILEW | Dieser Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus Unicode‑Zeichen besteht,<br/>             für die Grafik­ausgabe. |
| EMR_SETLAYOUT | Dieser Datensatz gibt die Reihenfolge an, in der Text und Grafiken gezeichnet werden. |
| EMR_SETLINKEDUFIS | Dieser Datensatz legt die UniversalFontIds verknüpfter Schriftarten fest, die bei der Zeichen­suche verwendet werden. |
| EMR_SETMAPMODE | Dieser Datensatz definiert den Abbildungsmodus des Wiedergabegeräte‑Kontexts. Der Abbildungsmodus<br/>             definiert die Maßeinheit, die verwendet wird, um Seiteneinheiten in Geräteeinheiten umzuwandeln,<br/>             und legt außerdem die Orientierung der x‑ und y‑Achse des Geräts fest. |
| EMR_SETMAPPERFLAGS | Dieser Datensatz gibt Parameter des Prozesses zur Zuordnung logischer Schriftarten zu physischen <br/>            Schriftarten an, der vom Schriftarten‑Mapper durchgeführt wird. |
| EMR_SETMETARGN | Dieser Datensatz schneidet die aktuelle Clipping‑Region des Wiedergabegeräte‑Kontexts mit der <br/>            aktuellen Meta‑Region und speichert die kombinierte Region als neue Meta‑Region. Die Clipping‑Region wird auf eine Null‑Region zurückgesetzt. |
| EMR_SETMITERLIMIT | Dieser Datensatz definiert die Grenze für die Länge von Gehrungsverbindungen für die Wiedergabe <br/>            Geräte-Kontext. |
| EMR_SETPALETTEENTRIES | Dieser Datensatz definiert RGB (Rot-Grün-Blau)-Farbwerte in einem Bereich von Einträgen <br/>            in einem LogPalette-Objekt. |
| EMR_SETPIXELV | Dieser Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten. |
| EMR_SETPOLYFILLMODE | Dieser Datensatz definiert den Füllmodus für Polygone. |
| EMR_SETROP2 | Dieser Datensatz definiert den binären Rasteroperationsmodus. |
| EMR_SETSTRETCHBLTMODE | Dieser Datensatz definiert den Streckungsmodus für Bitmaps. |
| EMR_SETTEXTALIGN | Dieser Datensatz definiert die Textausrichtung. |
| EMR_SETTEXTCOLOR | Dieser Datensatz definiert die aktuelle Textfarbe. |
| EMR_SETTEXTJUSTIFICATION | Dieser Datensatz gibt die Menge des zusätzlichen Raums an, der zu Trennzeichen für die Blocksatz<br/>             Zwecke hinzugefügt wird. |
| EMR_SETVIEWPORTEXTEX | Dieser Datensatz definiert die Ausdehnung des Ansichtsfensters. |
| EMR_SETVIEWPORTORGEX | Dieser Datensatz definiert den Ursprung des Ansichtsfensters. |
| EMR_SETWINDOWEXTEX | Dieser Datensatz definiert die Ausdehnung des Fensters. |
| EMR_SETWINDOWORGEX | Dieser Datensatz definiert den Fensterursprung. |
| EMR_SETWORLDTRANSFORM | Dieser Datensatz definiert eine zweidimensionale lineare Transformation zwischen dem Weltraum und <br/>            dem Seitenraum (für weitere Informationen siehe [MSDN-WRLDPGSPC]) für den Wiedergabegeräte-Kontext. <br/>            Diese Transformation kann verwendet werden, um Grafikausgaben zu skalieren, zu drehen, zu scheren oder zu übersetzen. |
| EMR_SMALLTEXTOUT | Dieser Datensatz gibt eine Zeichenkette aus. |
| EMR_STRETCHBLT | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel<br/>             Rechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Raster<br/>             Operation, wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen. |
| EMR_STRETCHDIBITS | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel <br/>            Rechteck an, optional in Kombination mit einem Pinselmuster, gemäß einer angegebenen Rasteroperation, <br/>            wobei die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen. |
| EMR_STROKEANDFILLPATH | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfads mit <br/>            dem aktuellen Stift nach und füllt das Innere mit dem aktuellen Pinsel. |
| EMR_STROKEPATH | Dieser Datensatz rendert den angegebenen Pfad mit dem aktuellen Stift. |
| EMR_TRANSPARENTBLT | Dieser Datensatz gibt eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Zielrechteck an,<br/>             wobei eine angegebene Farbe als transparent behandelt wird, und die Ausgabe bei Bedarf gestreckt oder komprimiert wird, um die Abmessungen des Ziels zu passen. |
| EMR_WIDENPATH | Dieser Datensatz definiert den aktuellen Pfad neu als den Bereich, der gemalt würde, wenn der Pfad <br/>            mit dem derzeit im Wiedergabegeräte-Kontext ausgewählten Stift nachgezogen würde. |
