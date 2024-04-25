---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Namespace enthält Typen MS-EMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 390
url: /de/aspose.imaging.fileformats.emf.emfplus.records/
---
Der Namespace enthält Typen [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | Der EmfPlusBeginContainer-Datensatz öffnet einen neuen Grafikzustandscontainer und gibt eine Transformation dafür an. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | Der EmfPlusBeginContainerNoParams-Datensatz öffnet einen neuen Grafikzustandscontainer. |
| [EmfPlusClear](./emfplusclear) | Der EmfPlusClear-Datensatz löscht den Ausgabekoordinatenraum und initialisiert ihn mit einer Hintergrundfarbe und Transparenz |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Die Clipping-Datensatztypen geben Clipping-Bereiche und -Operationen an. |
| [EmfPlusComment](./emfpluscomment) | Der EmfPlusComment-Datensatz gibt beliebige private Daten an. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Die Steuerdatensatztypen geben globale Parameter für die EMF+-Metadateiverarbeitung an. |
| [EmfPlusDrawArc](./emfplusdrawarc) | Der EmfPlusDrawArc-Datensatz gibt das Zeichnen des Bogens einer Ellipse an. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | Der EmfPlusDrawBeziers-Datensatz gibt das Zeichnen einer Folge verbundener Bezier-Kurven an. Die Reihenfolge für Bezier-Datenpunkte ist Startpunkt, Kontrollpunkt 1, Kontrollpunkt 2 und Endpunkt. Weitere Informationen finden Sie unter [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | Der EmfPlusDrawClosedCurve-Datensatz gibt das Zeichnen eines geschlossenen kardinalen Splines an |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | Der EmfPlusDrawCurve-Datensatz spezifiziert das Zeichnen eines kardinalen Spline HINWEIS: ObjectID (1 Byte): Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+-Objekttabelle zum Zeichnen der Kurve. Der Wert MUSS null bis einschließlich 63 sein. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | Der EmfPlusDrawDriverString-Datensatz spezifiziert die Textausgabe mit Zeichenpositionen. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | Der EmfPlusDrawEllipse-Datensatz gibt das Zeichnen einer Ellipse an. |
| [EmfPlusDrawImage](./emfplusdrawimage) | Der EmfPlusDrawImage-Datensatz gibt das Zeichnen eines skalierten Bildes an. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | Der EmfPlusDrawImagePoints-Datensatz spezifiziert das Zeichnen eines skalierten Bildes innerhalb eines Parallelogramms. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Die Zeichnungsdatensatztypen legen die Grafikausgabe fest. |
| [EmfPlusDrawLines](./emfplusdrawlines) | Der EmfPlusDrawlLines-Datensatz gibt das Zeichnen einer Reihe verbundener Linien an |
| [EmfPlusDrawPath](./emfplusdrawpath) | Der EmfPlusDrawPath-Datensatz gibt das Zeichnen eines Grafikpfads an. |
| [EmfPlusDrawPie](./emfplusdrawpie) | Der EmfPlusDrawPie-Datensatz spezifiziert das Zeichnen eines Abschnitts des Inneren einer Ellipse. |
| [EmfPlusDrawRects](./emfplusdrawrects) | Der EmfPlusDrawRects-Datensatz spezifiziert das Zeichnen einer Reihe von Rechtecken |
| [EmfPlusDrawString](./emfplusdrawstring) | Der EmfPlusDrawString-Datensatz spezifiziert die Textausgabe mit Zeichenfolgenformatierung |
| [EmfPlusEndContainer](./emfplusendcontainer) | Der EmfPlusEndContainer-Datensatz schließt einen Grafikstatus-Container, der zuvor durch eine Container-Beginn-Operation geöffnet wurde. |
| [EmfPlusEndOfFile](./emfplusendoffile) | Der EmfPlusEndOfFile-Datensatz gibt das Ende der EMF+-Daten in der Metadatei an. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | Der EmfPlusFillClosedCurve-Datensatz gibt an, das Innere eines geschlossenen Kardinal-Splines zu füllen |
| [EmfPlusFillEllipse](./emfplusfillellipse) | Der EmfPlusFillEllipse-Datensatz spezifiziert das Füllen des Inneren einer Ellipse |
| [EmfPlusFillPath](./emfplusfillpath) | Fill path record FLAGS: 16-Bit-Ganzzahl ohne Vorzeichen, die Auskunft darüber gibt, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 Bit): Dieses Bit gibt den Datentyp im Feld BrushId an. Falls gesetzt, spezifiziert BrushId eine Farbe als EmfPlusARGB-Objekt (Abschnitt 2.2.2.1). Wenn klar, enthält BrushId den Index eines EmfPlusBrush-Objekts (Abschnitt 2.2.1.1) in der EMF+-Objekttabelle. X (1 Bit): Reserviert und MUSS ignoriert werden. ObjectId (1 Byte): Der Index des EmfPlusPath-Objekts ( Abschnitt 2.2.1.6) zu füllen, in der EMF+ Objekttabelle. Der Wert MUSS null bis einschließlich 63 sein. |
| [EmfPlusFillPie](./emfplusfillpie) | Der EmfPlusFillPie-Datensatz spezifiziert das Füllen eines Abschnitts im Inneren einer Ellipse |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | Der EmfPlusFillPolygon-Datensatz gibt das Füllen des Inneren eines Polygons an. |
| [EmfPlusFillRects](./emfplusfillrects) | Der EmfPlusFillRects-Datensatz gibt an, das Innere einer Reihe von Rechtecken zu füllen |
| [EmfPlusFillRegion](./emfplusfillregion) | Der EmfPlusFillRegion-Datensatz gibt an, das Innere einer Grafikregion zu füllen |
| [EmfPlusGetDc](./emfplusgetdc) | Der EmfPlusGetDC-Eintrag gibt an, dass nachfolgende EMF-Einträge, die in der Metadatei gefunden werden, verarbeitet werden SOLLTEN. |
| [EmfPlusHeader](./emfplusheader) | Der EmfPlusHeader-Datensatz gibt den Beginn der EMF+-Daten in der Metadatei an. Der EmfPlusHeader-Datensatz MUSS in einen EMF EMR_COMMENT_EMFPLUS-Datensatz eingebettet werden, , der der Datensatz sein MUSS, der unmittelbar auf den EMF-Header in der Metadatei folgt. Der EMR_COMMENT_EMFPLUS-Datensatz ist in [MS-EMF] Abschnitt 2.3.3.2 angegeben. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | Der EmfPlusMultiplyWorldTransform-Datensatz multipliziert die aktuelle Weltraumtransformation mit einer angegebenen Transformationsmatrix. |
| [EmfPlusObject](./emfplusobject) | Der EmfPlusObject-Datensatz gibt ein Objekt zur Verwendung in Grafikoperationen an. Die Objektdefinition kann sich über mehrere Datensätze erstrecken, was durch den Wert des Felds „Flags“ angezeigt wird. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Die Object Record Types definieren wiederverwendbare Grafikobjekte. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | Der EmfPlusOffsetClip-Datensatz wendet eine Übersetzungstransformation auf den aktuellen Clipping-Bereich für den Weltraum an. Der neue aktuelle Clipping-Bereich wird auf das Ergebnis der Übersetzungstransformation gesetzt. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Die Eigenschaftsdatensatztypen geben Eigenschaften des Kontexts des Wiedergabegeräts an. |
| [EmfPlusRecord](./emfplusrecord) | Der EMF+-Basisdatensatztyp. |
| [EmfPlusResetClip](./emfplusresetclip) | Der EmfPlusResetClip-Datensatz setzt den aktuellen Clipping-Bereich für den Weltraum auf unendlich zurück. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | Der EmfPlusResetWorldTransform-Datensatz setzt die aktuelle Weltraumtransformation auf die Identifizierungsmatrix zurück. |
| [EmfPlusRestore](./emfplusrestore) | Der EmfPlusRestore-Datensatz stellt den durch einen angegebenen Index identifizierten Grafikstatus aus einem Stapel gespeicherter Grafikstatus wieder her. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | Der EmfPlusRotateWorldTransform-Datensatz führt eine Drehung an der aktuellen Weltraumtransformation durch. |
| [EmfPlusSave](./emfplussave) | Der EmfPlusSave-Datensatz speichert den Grafikzustand, identifiziert durch einen angegebenen Index, in einem Stapel gespeicherter Grafikzustände. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | Der EmfPlusScaleWorldTransform-Datensatz führt eine Skalierung der aktuellen Weltraumtransformation durch. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | Der EmfPlusSerializableObject-Datensatz definiert einen Parameterblock für Bildeffekte, der in einen Datenpuffer serialisiert wurde. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | Der EmfPlusSetAntiAliasMode-Datensatz gibt den Anti-Aliasing-Modus für die Textausgabe an. |
| [EmfPlusSetClipPath](./emfplussetclippath) | Der EmfPlusSetClipPath-Datensatz kombiniert den aktuellen Clipping-Bereich mit einem Grafikpfad. Der neue aktuelle Clipping-Bereich wird auf das Ergebnis der CombineMode-Operation gesetzt. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | Der EmfPlusSetClipRect-Datensatz kombiniert den aktuellen Clipping-Bereich mit einem Rechteck. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | Der EmfPlusSetClipRegion-Datensatz kombiniert den aktuellen Clipping-Bereich mit einem anderen Grafikbereich. Der neue aktuelle Clipping-Bereich wird auf das Ergebnis der Durchführung des CombineMode-Vorgangs für den vorherigen aktuellen Clipping-Bereich und das angegebene EmfPlusRegion-Objekt gesetzt. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | Der EmfPlusSetCompositingMode-Datensatz gibt an, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | Der EmfPlusSetCompositingQuality-Datensatz gibt die gewünschte Qualitätsstufe zum Erstellen zusammengesetzter Bilder aus mehreren Objekten an. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | Der EmfPlusSetInterpolationMode-Datensatz gibt an, wie die Bildskalierung, einschließlich Dehnung und Verkleinerung, durchgeführt wird. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | Der EmfPlusSetPageTransform-Datensatz gibt Skalierungsfaktoren und Einheiten zum Konvertieren von Koordinaten des Seitenbereichs in Koordinaten des Gerätebereichs an. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | Der EmfPlusSetPixelOffsetMode-Datensatz gibt an, wie Pixel in Bezug auf die -Koordinaten der Zeichenoberfläche zentriert werden. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | Der EmfPlusSetRenderingOrigin-Datensatz gibt den Rendering-Ursprung für die Grafikausgabe an. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | Der EmfPlusSetTextContrast-Datensatz gibt den Textkontrast gemäß dem Gamma-Korrekturwert an. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | Der EmfPlusSetTextRenderingHint-Datensatz gibt die Qualität der Textwiedergabe an, einschließlich des Anti-Aliasing-Typs. |
| [EmfPlusSetTsClip](./emfplussettsclip) | Der EmfPlusSetTSClip-Datensatz gibt Clipping-Bereiche im Grafikgerätekontext für einen Terminalserver an. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | Der EmfPlusSetTSGraphics-Datensatz gibt den Status eines Grafikgerätekontexts für einen Terminalserver an. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | Der EmfPlusSetWorldTransform-Datensatz legt die Welttransformation gemäß den Werten in einer angegebenen Transformationsmatrix fest. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | Die Zustandsdatensatztypen spezifizieren Operationen auf den Zustand des Kontexts des Wiedergabegeräts. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Die Terminalserver-Datensatztypen geben die Grafikverarbeitung auf einem Terminalserver an. Die folgenden sind EMF+ Terminalserver-Datensatztypen. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Die Transformationsdatensatztypen geben Eigenschaften und Transformationen in Koordinatenräumen an. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | Der EmfPlusTranslateWorldTransform-Datensatz führt eine Übersetzung der aktuellen Weltraumtransformation durch. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
