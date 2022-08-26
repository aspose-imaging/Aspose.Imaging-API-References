---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Namespace enthält Typen MS-EMF Enhanced Metafile Format. 2.3 EMF Records
type: docs
weight: 360
url: /de/net/aspose.imaging.fileformats.emf.emf.records/
---
Der Namespace enthält Typen [MS-EMF]: Enhanced Metafile Format. 2.3 EMF Records

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Dieser Datensatz bricht eine Pfadklammer ab oder verwirft den Pfad aus einer geschlossenen Pfadklammer. |
| [EmfAlphaBlend](./emfalphablend) | Der EMR_ALPHABLEND-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, einschließlich Alpha-Transparenzdaten, entsprechend einer spezifizierten Mischoperation. |
| [EmfAngleArc](./emfanglearc) | Der EMR_ANGLEARC-Datensatz gibt ein Liniensegment eines Bogens an. Das Liniensegment wird von der aktuellen Position zum Anfang des Bogens gezeichnet. Der Bogen wird entlang des Umfangs eines Kreises mit dem angegebenen Radius und Mittelpunkt gezeichnet. Die Länge des Bogens wird durch die gegebenen Start- und Sweep-Winkel definiert |
| [EmfArc](./emfarc) | Der EMR_ARC-Datensatz gibt einen elliptischen Bogen an. |
| [EmfArcTo](./emfarcto) | Der EMR_ARCTO-Datensatz gibt einen Ellipsenbogen an. Es setzt die aktuelle Position auf den Endpunkt des Bogens zurück. |
| [EmfBeginPath](./emfbeginpath) | Dieser Datensatz öffnet eine Pfadklammer im Kontext des aktuellen Wiedergabegeräts. Nachdem eine Pfadklammer geöffnet ist, kann eine Anwendung mit der Verarbeitung von Datensätzen beginnen, um die Punkte zu definieren, die im Pfad liegen. Eine Anwendung MUSS eine offene Pfadklammer schließen, indem sie den EMR_ENDPATH verarbeitet Datensatz. Wenn eine Anwendung den Datensatz EMR_BEGINPATH verarbeitet, MÜSSEN alle vorherigen Pfade aus dem Kontext des Wiedergabegeräts verworfen werden. |
| [EmfBitBlt](./emfbitblt) | Der EMR_BITBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, entsprechend einer spezifizierten Rasteroperation. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | Die Bitmap-Datensatztypen führen Blockübertragungen von Bitmap-Bildern durch. |
| [EmfChord](./emfchord) | Der EMR_CHORD-Datensatz gibt eine Sehne an, bei der es sich um einen Bereich handelt, der durch den Schnittpunkt einer -Ellipse und eines als Sekante bezeichneten Liniensegments begrenzt wird. Der Akkord wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| [EmfClippingRecordType](./emfclippingrecordtype) | Die Clipping-Datensatztypen spezifizieren und verwalten Clipping-Bereiche. Hinweis Der Datensatz EMR_SETMETARGN gibt keine Parameter an. |
| [EmfCloseFigure](./emfclosefigure) | Dieser Datensatz schließt eine offene Figur in einem Pfad. Die Verarbeitung des EMR_CLOSEFIGURE-Datensatzes MUSS die Figur schließen, indem eine Linie von der aktuellen Position zum ersten Punkt der Figur gezogen wird, und dann MUSS er die Linien mit verbinden, indem er den Linienverbindungsstil verwendet. Wenn eine Figur geschlossen wird, indem der EMR_LINETO-Datensatz anstelle des EMR_CLOSEFIGURE-Datensatzes verarbeitet wird, werden Endkappen verwendet, um die Ecke anstelle einer Verbindung zu erstellen. EMR_LINETO ist in Abschnitt 2.3.5.13. angegeben open path Klammer im Kontext des Wiedergabegeräts. Eine Figur in einem Pfad ist offen, es sei denn, sie wird durch die Verarbeitung dieses Datensatzes explizit geschlossen. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | Der Datensatz EMR_COLORCORRECTPALETTE gibt an, wie die Einträge eines logischen palette -Objekts mithilfe von WCS 1.0-Werten korrigiert werden. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | Der EMR_COLORMATCHTOTargetW-Datensatz gibt an, ob ein Farbabgleich mit einem Farbprofil durchgeführt werden soll, das in einer Datei mit einem aus Unicode-Zeichen bestehenden Namen angegeben ist. |
| [EmfComment](./emfcomment) | Der EMR_COMMENT-Datensatz enthält beliebige private Daten. Hinweis Felder, die in diesem Abschnitt nicht beschrieben werden, werden in Abschnitt 2.3.3. angegeben. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | Der Datensatz EMR_COMMENT_BEGINGRUPPE gibt den Beginn einer Gruppe von Zeichnungsdatensätzen an. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | Der Datensatz EMR_COMMENT_EMFPLUS enthält eingebettete EMF+-Datensätze. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.3. spezifiziert. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | Der Datensatz EMR_COMMENT_EMFSPOOL enthält eingebettete EMFSPOOL-Datensätze. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.3. spezifiziert. |
| [EmfCommentEndGroup](./emfcommentendgroup) | Der Datensatz EMR_COMMENT_ENDGROUP gibt das Ende einer Gruppe von Zeichnungsdatensätzen an. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | Der Datensatz EMR_COMMENT_MULTIFORMATS gibt ein Bild in mehreren Grafikformaten an. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | Die Datensatztypen EMR_COMMENT_PUBLIC geben Erweiterungen zur EMF-Verarbeitung an. |
| [EmfCommentRecordType](./emfcommentrecordtype) | Die Kommentar-Datensatztypen definieren Formate zum Spezifizieren willkürlicher privater Daten, zum Einbetten von Datensätzen in andere Metadateiformate und zum Hinzufügen neuer oder spezieller Befehle. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | Der Datensatz EMR_COMMENT_WINDOWS_METAFILE gibt ein Bild in einer eingebetteten WMF-Metadatei an. |
| [EmfControlRecordType](./emfcontrolrecordtype) | Die Steuerdatensatztypen definieren Anfang und Ende einer EMF-Metadatei und Eigenschaften der Metadatei. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | Der Datensatz EMR_CREATEBRUSHINDIRECT definiert einen logischen Pinsel für Grafikoperationen. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | Der EMR_CREATECOLORSPACE-Datensatz erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem -Namen, der aus ASCII-Zeichen besteht. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | Der Datensatz EMR_CREATECOLORSPACEW erstellt ein logisches Farbraumobjekt aus einem Farbprofil mit einem aus Unicode-Zeichen bestehenden Namen. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | Der Datensatz EMR_CREATEDIBPATTERNBRUSHPT definiert einen Musterpinsel für Grafikoperationen. Das -Muster wird durch eine DIB angegeben. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | Der Datensatz EMR_CREATEMONOBRUSH definiert einen monochromen Musterpinsel für Grafikoperationen. Das Muster wird durch eine monochrome DIB angegeben. |
| [EmfCreatePalette](./emfcreatepalette) | Der Datensatz EMR_CREATEPALETTE definiert eine logische Palette für Grafikoperationen. |
| [EmfCreatePen](./emfcreatepen) | Der Datensatz EMR_CREATEPEN definiert einen logischen Stift für Grafikoperationen. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | Der Datensatz EMR_DELETECOLORSPACE löscht ein logisches Farbraumobjekt. |
| [EmfDeleteObject](./emfdeleteobject) | Der Datensatz EMR_DELETEOBJECT löscht ein Grafikobjekt, das durch seinen Index in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angegeben ist. |
| [EmfDrawEscape](./emfdrawescape) | Der Datensatz EMR_DRAWESCAPE übergibt willkürliche Informationen an einen Druckertreiber. Die Absicht ist, dass die Informationen dazu führen, dass die Zeichnung fertig ist. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | Die Zeichnungsdatensatztypen führen Grafikzeichnungen aus. |
| [EmfEllipse](./emfellipse) | Der Datensatz EMR_ELLIPSE gibt eine Ellipse an. Der Mittelpunkt der Ellipse ist der Mittelpunkt des angegebenen Begrenzungsrechtecks. Die Ellipse wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| [EmfEndPath](./emfendpath) | Dieser Datensatz schließt eine Pfadklammer und wählt den durch die Klammer definierten Pfad in den Kontext des Wiedergabegeräts. |
| [EmfEof](./emfeof) | Der EMR_EOF-Datensatz gibt das Ende der Metadatei an und gibt eine Palette an. |
| [EmfEscapeRecordType](./emfescaperecordtype) | Die Escape-Datensatztypen führen Druckertreiberfunktionen aus. |
| [EmfExcludeClipRect](./emfexcludecliprect) | Der EMR_EXCLUDECLIPRECT-Datensatz gibt einen neuen Clipping-Bereich an, der aus dem vorhandenen -Clipping-Bereich minus dem angegebenen Rechteck besteht. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.2. spezifiziert. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | Der Datensatz EMR_EXTCREATEFONTINDIRECTW definiert eine logische Schriftart für Grafikoperationen. |
| [EmfExtCreatePen](./emfextcreatepen) | Der Datensatz EMR_EXTCREATEPEN definiert einen erweiterten logischen Stift für Grafikoperationen. Eine optionale DIB kann als Linienstil angegeben werden. |
| [EmfExtEscape](./emfextescape) | Der Datensatz EMR_EXTESCAPE übergibt willkürliche Informationen an einen Druckertreiber. Die Absicht ist, dass die -Informationen nicht dazu führen, dass eine Zeichnung erstellt wird. |
| [EmfExtFloodFill](./emfextfloodfill) | Der Datensatz EMR_EXTFLOODFILL füllt einen Bereich der Anzeigeoberfläche mit dem aktuellen Pinsel |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | Der Datensatz EMR_EXTSELECTCLIPRGN kombiniert den angegebenen Bereich mit dem aktuellen Clip-Bereich unter Verwendung des angegebenen Modus. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.2. spezifiziert. |
| [EmfExtTextOutA](./emfexttextouta) | Der Datensatz EMR_EXTTEXTOUTA zeichnet eine ASCII-Textzeichenfolge unter Verwendung der aktuellen Schriftart und Textfarben. |
| [EmfExtTextOutW](./emfexttextoutw) | Der Datensatz EMR_EXTTEXTOUTW zeichnet eine ASCII-Textzeichenfolge unter Verwendung der aktuellen Schriftart und Textfarben. |
| [EmfFillPath](./emffillpath) | Der Datensatz EMR_FILLPATH schließt alle offenen Figuren im aktuellen Pfad und füllt das Innere des Pfads um unter Verwendung des aktuellen Pinsel- und Polygonfüllmodus. |
| [EmfFillRgn](./emffillrgn) | Der Datensatz EMR_FILLRGN füllt den angegebenen Bereich mithilfe des angegebenen Pinsels. |
| [EmfFlatternPath](./emfflatternpath) | Dieser Datensatz transformiert alle Kurven im ausgewählten Pfad in den Kontext des Wiedergabegeräts ; Jede Kurve MUSS in eine Folge von Linien umgewandelt werden. |
| [EmfForceUfiMapping](./emfforceufimapping) | Der EMR_FORCEUFIMAPPING-Datensatz zwingt den Font-Mapper, Schriftarten basierend auf ihrer UniversalFontId anstelle ihrer LogFont-Informationen (Abschnitt 2.2.13) abzugleichen. |
| [EmfFrameRgn](./emfframergn) | Der Datensatz EMR_FRAMERGN zeichnet mit dem angegebenen Pinsel einen Rahmen um den angegebenen Bereich. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | Der Datensatz EMR_GLSBOUNDEDRECORD gibt eine OpenGL-Funktion mit einem Begrenzungsrechteck für die Ausgabe an. |
| [EmfGlsRecord](./emfglsrecord) | Der Datensatz EMR_GLSRECORD gibt eine OpenGL-Funktion an. |
| [EmfGradientFill](./emfgradientfill) | Der Datensatz EMR_GRADIENTFILL spezifiziert das Füllen von Rechtecken oder Dreiecken mit Farbverläufen. |
| [EmfIntersectClipRect](./emfintersectcliprect) | Der Datensatz EMR_INTERSECTCLIPRECT gibt einen neuen Clipping-Bereich aus dem Schnittpunkt des aktuellen Clipping-Bereichs und des angegebenen Rechtecks an. Hinweis Felder, die in diesem Abschnitt nicht beschrieben sind, werden in Abschnitt 2.3.2. spezifiziert. |
| [EmfInvertRgn](./emfinvertrgn) | Der Datensatz EMR_INVERTRGN invertiert die Farben in der angegebenen Region. |
| [EmfLineTo](./emflineto) | Der EMR_LINETO-Datensatz gibt eine Linie von der aktuellen Position bis zum (aber nicht einschließlich) des angegebenen Punkts an. Er setzt die aktuelle Position auf den angegebenen Punkt zurück. |
| [EmfMaskBlt](./emfmaskblt) | Der EMR_MASKBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Rechteck, optional in Kombination mit einem Pinselmuster und mit der Anwendung einer Farbmasken- -Bitmap, gemäß spezifizierten Vordergrund- und Hintergrund-Rasteroperationen. |
| [EmfMetafileHeader](./emfmetafileheader) | Die EMR_HEADER-Datensatztypen definieren die Startpunkte von EMF-Metadateien und geben Eigenschaften des Geräts an, auf dem das Bild in der Metadatei erstellt wurde. Die Informationen im Header-Datensatz machen es möglich, dass EMF-Metadateien von einem bestimmten Ausgabegerät unabhängig sind. Der Wert des Felds Größe kann verwendet werden, um zwischen den verschiedenen EMR_HEADER-Datensatztypen zu unterscheiden, die weiter oben in diesem Abschnitt aufgeführt sind. Es gibt drei Möglichkeiten headers: Der Basisheader, der der EmfMetafileHeader-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 88 Bytes groß und enthält ein Header-Objekt. Der erste Erweiterungsheader, der der EmfMetafileHeaderExtension1-Datensatz ist. Die feste Größe Teil dieses Headers ist 100 Bytes groß und enthält ein Header-Objekt und ein HeaderExtension1-Objekt (Abschnitt 2.2.10). Der zweite Erweiterungs-Header, der der EmfMetafileHeaderExtension2-Datensatz ist. Der Teil mit fester Größe dieses Headers ist 108 Bytes, und es enthält ein Header-Objekt, ein HeaderExtension1-Objekt und ein HeaderExtension2-Objekt (Abschnitt 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | Der EmfMetafileHeaderExtension1-Datensatz ist der Header-Datensatz, der in der ersten Erweiterung von EMF-Metadateien verwendet wird. Nach dem EmfHeaderExtension1-Feld sind die verbleibenden Felder optional und können in beliebiger Reihenfolge vorhanden sein. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | Der EmfMetafileHeaderExtension2-Datensatz ist der Header-Datensatz, der in der zweiten Erweiterung von EMF -Metadateien verwendet wird. Nach dem EmfHeaderExtension2-Feld sind die restlichen Felder optional und können in beliebiger Reihenfolge vorhanden sein. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | Der Datensatz EMR_MODIFYWORLDTRANSFORM modifiziert den aktuellen World-Space in Page-Space umzuwandeln im Kontext des Wiedergabegeräts. |
| [EmfMoveToEx](./emfmovetoex) | Der EMR_MOVETOEX-Datensatz gibt die Koordinaten der neuen aktuellen Position in logischen Einheiten an. |
| [EmfNamedEscape](./emfnamedescape) | Der Datensatz MR_NAMEDESCAPE übergibt willkürliche Informationen an einen angegebenen Druckertreiber. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | Die Datensatztypen zur Objekterstellung erstellen Grafikobjekte. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | Die Datensatztypen zur Objektmanipulation verwalten und ändern Grafikobjekte. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | Der Datensatz EMR_OFFSETCLIPRGN verschiebt den aktuellen Clipping-Bereich im Kontext des Wiedergabegeräts um die angegebenen Offsets. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | Die OpenGL-Eintragstypen spezifizieren OpenGL-Funktionen. |
| [EmfPaintRgn](./emfpaintrgn) | Der EMR_PAINTRGN-Datensatz malt den angegebenen Bereich unter Verwendung des aktuell ausgewählten Pinsels in den Kontext des -Wiedergabegeräts. |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | Die Datensatztypen für Pfadklammern spezifizieren und manipulieren Pfade in Pfadklammern. Hinweis: Keiner der Datensätze für Pfadklammern gibt Parameter an. |
| [EmfPie](./emfpie) | Der EMR_PIE-Datensatz gibt einen tortenförmigen Keil an, der durch den Schnittpunkt einer Ellipse und zwei -Radialen begrenzt wird. Der Kreis wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| [EmfPixelFormat](./emfpixelformat) | Der EMR_PIXELFORMAT-Datensatz gibt das für Grafikoperationen zu verwendende Pixelformat an. |
| [EmfPlgBlt](./emfplgblt) | Der EMR_PLGBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem Ziel- -Parallelogramm unter Anwendung einer Farbmasken-Bitmap. |
| [EmfPolyBezier](./emfpolybezier) | Der EMR_POLYBEZIER-Datensatz gibt eine oder mehrere Bezier-Kurven an. |
| [EmfPolyBezier16](./emfpolybezier16) | Der Datensatz EMR_POLYBEZIER16 gibt eine oder mehrere Bezier-Kurven an. Die Kurven werden mit dem aktuellen Stift gezeichnet. |
| [EmfPolyBezierTo](./emfpolybezierto) | Der Datensatz EMR_POLYBEZIERTO gibt eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position an. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | Der Datensatz EMR_POLYBEZIERTO16 gibt eine oder mehrere Bezier-Kurven basierend auf der aktuellen Position an. |
| [EmfPolyDraw](./emfpolydraw) | Der EMR_POLYDRAW-Datensatz gibt eine Reihe von Liniensegmenten und Bezier-Kurven an. |
| [EmfPolyDraw16](./emfpolydraw16) | Der Datensatz EMR_POLYDRAW16 gibt eine Reihe von Liniensegmenten und Bézier-Kurven an. |
| [EmfPolygon](./emfpolygon) | Der Datensatz EMR_POLYGON gibt ein Polygon an, das aus zwei oder mehr Eckpunkten besteht, die durch gerade Linien verbunden sind. |
| [EmfPolygon16](./emfpolygon16) | Der Datensatz EMR_POLYGON16 gibt ein Polygon an, das aus zwei oder mehr Scheitelpunkten besteht, die durch gerade Linien verbunden sind. Das Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel und Polygon-Füllmodus gefüllt. Das Polygon wird automatisch geschlossen, indem eine Linie vom letzten Eckpunkt zum ersten gezogen wird. |
| [EmfPolyline](./emfpolyline) | Der EMR_POLYLINE-Datensatz gibt eine Reihe von Liniensegmenten an, indem er die Punkte in dem angegebenen Array verbindet. |
| [EmfPolyline16](./emfpolyline16) | Der EMR_POLYLINE16-Datensatz gibt eine Reihe von Liniensegmenten an, indem die Punkte im angegebenen Array verbunden werden. |
| [EmfPolylineTo](./emfpolylineto) | Der Datensatz EMR_POLYLINETO gibt basierend auf der aktuellen Position eine oder mehrere gerade Linien an. |
| [EmfPolylineTo16](./emfpolylineto16) | Der Datensatz EMR_POLYLINETO16 gibt basierend auf der aktuellen Position eine oder mehrere gerade Linien an. Mit dem aktuellen Stift wird eine Linie von der aktuellen Position zum ersten Punkt gezogen, der durch das aPoints-Feld angegeben wird. Für jede weitere Linie wird vom Endpunkt der vorherigen Linie bis zum nächsten durch aPoints angegebenen Punkt gezeichnet. |
| [EmfPolyPolygon](./emfpolypolygon) | Der Datensatz EMR_POLYPOLYGON gibt eine Reihe geschlossener Polygone an. |
| [EmfPolyPolygon16](./emfpolypolygon16) | Der Datensatz EMR_POLYPOLYGON16 gibt eine Reihe geschlossener Polygone an. Jedes Polygon wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel- und Polygon-Füllmodus gefüllt. Die von diesem Datensatz gezeichneten Polygone können sich überlappen. |
| [EmfPolyPolyline](./emfpolypolyline) | Der Datensatz EMR_POLYPOLYLINE gibt mehrere Serien verbundener Liniensegmente an. |
| [EmfPolyPolyline16](./emfpolypolyline16) | Der Datensatz EMR_POLYPOLYLINE16 gibt mehrere Serien verbundener Liniensegmente an. |
| [EmfPolyTextOutA](./emfpolytextouta) | Der Datensatz EMR_POLYTEXTOUTA zeichnet eine oder mehrere ASCII-Textzeichenfolgen unter Verwendung der aktuellen Schriftart und Textfarben. |
| [EmfPolyTextOutW](./emfpolytextoutw) | Der Datensatz EMR_POLYTEXTOUTW zeichnet eine oder mehrere Unicode-Textzeichenfolgen unter Verwendung der aktuellen Schriftart und Textfarben. |
| [EmfRealizePalette](./emfrealizepalette) | Dieser Datensatz ordnet Paletteneinträge aus dem aktuellen LogPalette-Objekt (Abschnitt 2.2.17) der system_palette zu. Dieser EMF-Datensatz gibt keine Parameter an. |
| [EmfRecord](./emfrecord) | Basisklasse für EMF-Records Alle EMF-Records MÜSSEN eine Länge haben, die ein Vielfaches von 4 Bytes ist. Dies wird in den generischen Strukturen der vorhergehenden EMF-Record-Typen dargestellt, indem an den Enden dieser Strukturen gegebenenfalls AlignmentPadding fields eingefügt werden. Der Inhalt von AlignmentPadding fields MUSS immer ignoriert werden. Der Kürze halber werden diese Felder nicht in jeder einzelnen EMF -Datensatzdefinition angezeigt. |
| [EmfRectangle](./emfrectangle) | Der Datensatz EMR_RECTANGLE zeichnet ein Rechteck. Das Rechteck wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| [EmfResizePalette](./emfresizepalette) | Der Datensatz EMR_RESIZEPALETTE erhöht oder verringert die Größe eines vorhandenen LogPalette-Objekts (Abschnitt 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | Der Datensatz EMR_RESTOREDC stellt den Kontext des Wiedergabegeräts im angegebenen Zustand wieder her. Der Kontext des Wiedergabegeräts wird wiederhergestellt, indem Zustandsinformationen aus einem Stapel entnommen werden, der von früheren EMR_SAVEDC-Datensätzen (Abschnitt 2.3.11) erstellt wurde. |
| [EmfRop4](./emfrop4) | Eine quaternäre Rasteroperation, die ternäre Rasteroperationen für die Vorder- und Hintergrundfarben einer Bitmap angibt. Diese Werte definieren, wie die Farbdaten des Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden sollen. |
| [EmfRoundRect](./emfroundrect) | Der Datensatz EMR_ROUNDRECT gibt ein Rechteck mit abgerundeten Ecken an. Das Rechteck wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt. |
| [EmfSaveDc](./emfsavedc) | Speichert den aktuellen Zustand des Kontexts des Wiedergabegeräts in einem -Stack von Zuständen, die von vorhergehenden EMR_SAVEDC -Datensätzen gespeichert wurden, falls vorhanden. Der Zustand besteht aus Grafikeigenschaften und Objekten, einschließlich der aktuell ausgewählten Bitmap, Pinsel, Palette, Schriftart, Stift und Bereich. Ein EMR_RESTOREDC-Datensatz wird verwendet, um den Zustand wiederherzustellen. Dieser EMF-Datensatz gibt keine Parameter an. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | Der EMR_SCALEVIEWPORTEXTEX-Datensatz gibt den Darstellungsbereich für einen Gerätekontext neu an, indem er die -Verhältnisse verwendet, die durch die angegebenen Multiplikanden und Divisoren gebildet werden. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | Der EMR_SCALEWINDOWEXTEX-Datensatz spezifiziert das Fenster für einen Wiedergabegerätekontext durch unter Verwendung der Verhältnisse, die durch die angegebenen Multiplikanden und Divisoren gebildet werden. |
| [EmfSelectClipPath](./emfselectclippath) | Der EMR_SELECTCLIPPATH-Datensatz gibt den aktuellen Pfad als Clipping-Region für einen -Wiedergabegerätekontext an und kombiniert die neue Region mit einer beliebigen vorhandenen Clipping-Region unter Verwendung des angegebenen Modus. |
| [EmfSelectObject](./emfselectobject) | Der EMR_SELECTOBJECT-Datensatz fügt ein Grafikobjekt zum aktuellen Metadatei-Wiedergabegerät -Kontext hinzu. Das Objekt wird entweder durch seinen Index in der EMF-Objekttabelle (Abschnitt 3.1.1.1) oder durch seinen -Wert aus der StockObject-Enumeration (Abschnitt 2.1.31) spezifiziert. |
| [EmfSelectPalette](./emfselectpalette) | Der Datensatz EMR_SELECTPALETTE gibt eine logische Palette für den Kontext des Wiedergabegeräts an. |
| [EmfSetArcDirection](./emfsetarcdirection) | Der Datensatz EMR_SETARCDIRECTION gibt die Zeichenrichtung an, die für die Bogen- und Rechteckausgabe verwendet werden soll. |
| [EmfSetBkColor](./emfsetbkcolor) | Der Datensatz EMR_SETBKCOLOR gibt die Hintergrundfarbe an. |
| [EmfSetBkMode](./emfsetbkmode) | Der Datensatz EMR_SETBKMODE gibt den Hintergrundmischmodus des Wiedergabegerätekontexts an. Der Hintergrundmischmodus wird mit Text, schraffierten Pinseln und Stiftstilen verwendet, die keine durchgezogenen Linien sind. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | Der Datensatz EMR_SETBRUSHORGEX gibt den Ursprung des aktuellen Pinsels an. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | Der Datensatz EMR_SETCOLORADJUSTMENT gibt Farbanpassungseigenschaften im Gerätekontext Wiedergabe an. |
| [EmfSetColorSpace](./emfsetcolorspace) | Der Datensatz EMR_SETCOLORSPACE definiert das aktuelle logische Farbraumobjekt für Grafikoperationen. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | Der EMR_SETDIBITSTODEVICE-Datensatz spezifiziert eine Blockübertragung von Pixeln von spezifizierten Abtastzeilen von einer Quellbitmap zu einem Zielrechteck. |
| [EmfSetIcmMode](./emfseticmmode) | Der Datensatz EMR_SETICMMODE gibt den Modus des Image Color Management (ICM) für Grafikoperationen an. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | Der EMR_SETICMPROFILEA-Datensatz gibt ein Farbprofil in einer Datei an, deren Name aus ASCII -Zeichen besteht, für die Grafikausgabe. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | Der Datensatz EMR_SETICMPROFILEW gibt ein Farbprofil in einer Datei an, deren Name aus Unicode-Zeichen besteht, für die Grafikausgabe. |
| [EmfSetLayout](./emfsetlayout) | Der Datensatz EMR_SETLAYOUT gibt die Reihenfolge an, in der Text und Grafiken gezeichnet werden. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | Der EMR_SETLINKEDUFIS-Datensatz legt die UniversalFontIds (Abschnitt 2.2.27) der verknüpften Schriftarten so fest, dass sie während der Zeichensuche verwendet werden. |
| [EmfSetMapMode](./emfsetmapmode) | Der Datensatz EMR_SETMAPMODE gibt den Zuordnungsmodus des Kontexts des Wiedergabegeräts an. Der Zuordnungsmodus gibt die Maßeinheit an, die zum Umwandeln von Seitenbereichseinheiten in Gerätebereichseinheiten verwendet wird, und gibt auch die Ausrichtung der X- und Y-Achse des Geräts an. |
| [EmfSetMapperFlags](./emfsetmapperflags) | Der EMR_SETMAPPERFLAGS-Datensatz gibt Parameter für den Prozess des Abgleichs logischer Schriftarten mit physischen Schriftarten an, der vom Schriftart-Mapper ausgeführt wird. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter setzt die aktuelle Meta-Region mit der aktuellen Clipping-Region , um eine neue Meta-Region für den Kontext des Wiedergabegeräts zu bilden. Der aktuelle Clipping-Bereich SOLLTE auf null zurückgesetzt werden. Dieser EMF-Datensatz gibt keine Parameter an. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | Der Datensatz EMR_SETMITERLIMIT gibt die Grenze für die Länge von Gehrungsverbindungen für den Kontext des Wiedergabegeräts an. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | Der Datensatz EMR_SETPALETTEENTRIES definiert RGB-Farbwerte in einem Bereich von Einträgen für ein vorhandenes LogPalette (Abschnitt 2.2.17)-Objekt. |
| [EmfSetPixelV](./emfsetpixelv) | Der Datensatz EMR_SETPIXELV definiert die Farbe des Pixels an den angegebenen logischen Koordinaten. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | Der Datensatz EMR_SETPOLYFILLMODE definiert den Polygonfüllmodus. |
| [EmfSetRop2](./emfsetrop2) | Der Datensatz EMR_SETROP2 definiert einen binären Raster-Betriebsmodus. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | Der Datensatz EMR_SETSTRETCHBLTMODE gibt den Bitmap-Stretch-Modus an. |
| [EmfSetTextAlign](./emfsettextalign) | Der Datensatz EMR_SETTEXTALIGN gibt die Textausrichtung an. |
| [EmfSetTextColor](./emfsettextcolor) | Der Datensatz EMR_SETTEXTCOLOR definiert die aktuelle Textfarbe. |
| [EmfSetTextJustification](./emfsettextjustification) | Der EMR_SETTEXTJUSTIFICATION-Datensatz gibt die Menge an zusätzlichem Leerzeichen an, die zu break -Zeichen für die Textausrichtung hinzugefügt werden soll. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | Der Datensatz EMR_SETVIEWPORTEXTEX definiert die Ausdehnung des Darstellungsbereichs. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | Der Datensatz EMR_SETVIEWPORTORGEX definiert den Ursprung des Ansichtsfensters. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | Der Datensatz EMR_SETWINDOWEXTEX definiert die Fensterausdehnung. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | Der Datensatz EMR_SETWINDOWORGEX definiert den Fensterursprung. |
| [EmfSetWorldTransform](./emfsetworldtransform) | Der EMR_SETWORLDTRANSFORM-Datensatz gibt eine Transformation für die aktuelle World-Space-to-Page-Space-Transformation im Kontext des Wiedergabegeräts an. |
| [EmfSmallTextOut](./emfsmalltextout) | Der Datensatz EMR_SMALLTEXTOUT gibt eine Zeichenfolge aus. |
| [EmfStateRecordType](./emfstaterecordtype) | Die Zustandsdatensatztypen spezifizieren und verwalten Grafikeigenschaften, die den Zustand des Kontexts des Wiedergabegeräts definieren. |
| [EmfStretchBlt](./emfstretchblt) | Der EMR_STRETCHBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, gemäß einer spezifizierten raster -Operation, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich . |
| [EmfStretchDiBits](./emfstretchdibits) | Der EMR_STRETCHDIBITS-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quell-Bitmap zu einem -Zielrechteck, optional in Kombination mit einem Pinselmuster, entsprechend einer spezifizierten Raster- -Operation, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls notwendig. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | Der Datensatz EMR_STROKEANDFILLPATH schließt alle offenen Figuren in einem Pfad, streicht den Umriss des Pfads mit dem aktuellen Stift und füllt sein Inneres mit dem aktuellen Pinsel. |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH-Klasse |
| [EmfTransformRecordType](./emftransformrecordtype) | Die Transformationsdatensatztypen spezifizieren und modifizieren World-Space-to-Page-Space-Transformationen. |
| [EmfTransparentBlt](./emftransparentblt) | Der EMR_TRANSPARENTBLT-Datensatz spezifiziert eine Blockübertragung von Pixeln von einer Quellbitmap zu einem -Zielrechteck, wobei eine angegebene Farbe als transparent behandelt wird, wobei die Ausgabe gestreckt oder komprimiert wird, um sie an die Abmessungen des Ziels anzupassen, falls erforderlich |
| [EmfVertexData](./emfvertexdata) | Objekte, die die Scheitelpunkte von Rechtecken oder Dreiecken und die ihnen entsprechenden Farben angeben. |
| [EmfWidenPath](./emfwidenpath) | Dieser Datensatz definiert den aktuellen Pfad neu als den Bereich, der gezeichnet würde, wenn der Pfad mit dem Stift gezeichnet würde, der derzeit im Kontext des Wiedergabegeräts ausgewählt ist. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
