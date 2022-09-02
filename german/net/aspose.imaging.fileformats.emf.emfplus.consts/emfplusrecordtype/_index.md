---
title: EmfPlusRecordType
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die RecordType-Enumeration definiert Datensatztypen die in EMF-Metadateien verwendet werden.
type: docs
weight: 5030
url: /de/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

Die RecordType-Enumeration definiert Datensatztypen, die in EMF+-Metadateien verwendet werden.

```csharp
public enum EmfPlusRecordType : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Dieser Datensatz gibt den Anfang von EMF+-Daten in der Metadatei an. Es MUSS in den ersten EMF-Eintrag nach eingebettet werden[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) Aufzeichnung ([MS-EMF] Abschnitt 2.3.4.2 Aufzeichnung). |
| EmfPlusEndOfFile | `16386` | Dieser Datensatz gibt das Ende der EMF+-Daten in der Metadatei an. |
| EmfPlusComment | `16387` | Dieser Datensatz enthält beliebige private Daten. |
| EmfPlusGetDC | `16388` | Dieser Datensatz gibt an, dass nachfolgende EMF-Datensätze, die in der Metadatei gefunden werden, verarbeitet werden SOLLTEN. EMF-Datensätze werden nicht mehr verarbeitet, wenn der nächste EMF+-Datensatz gefunden wird. |
| EmfPlusMultiFormatStart | `16389` | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EmfPlusMultiFormatSection | `16390` | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EmfPlusMultiFormatEnd | `16391` | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EmfPlusObject | `16392` | Dieser Datensatz gibt ein Objekt zur Verwendung in Grafikoperationen an. |
| EmfPlusClear | `16393` | Dieser Datensatz löscht die Ausgabe`Raum koordinieren` und initialisiert es mit einer bestimmten Hintergrundfarbe und Transparenz. |
| EmfPlusFillRects | `16394` | Dieser Datensatz definiert, wie das Innere einer Reihe von Rechtecken mit einem bestimmten Pinsel gefüllt wird. |
| EmfPlusDrawRects | `16395` | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe von Rechtecken. |
| EmfPlusFillPolygon | `16396` | Dieser Datensatz definiert die Daten zum Füllen des Inneren eines Polygons mit einem bestimmten Pinsel. |
| EmfPlusDrawLines | `16397` | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe verbundener Linien. |
| EmfPlusFillEllipse | `16398` | Dieser Datensatz definiert, wie das Innere einer Ellipse mit einem bestimmten Pinsel gefüllt wird. |
| EmfPlusDrawEllipse | `16399` | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Ellipse. |
| EmfPlusFillPie | `16400` | Dieser Datensatz definiert, wie ein Abschnitt eines inneren Abschnitts einer Ellipse mit einem bestimmten Pinsel gefüllt wird. |
| EmfPlusDrawPie | `16401` | Dieser Datensatz definiert Stiftstriche zum Zeichnen eines Abschnitts einer Ellipse. |
| EmfPlusDrawArc | `16402` | Der Datensatz definiert Stiftstriche zum Zeichnen eines Ellipsenbogens. |
| EmfPlusFillRegion | `16403` | Dieser Datensatz definiert, wie das Innere einer Region mit einem bestimmten Pinsel gefüllt wird. |
| EmfPlusFillPath | `16404` | Der Datensatz definiert, wie das Innere der Figuren, die in einem Grafikpfad definiert sind, mit einem bestimmten Pinsel gefüllt wird. Ein Pfad ist ein Objekt, das eine beliebige Folge von Linien, Kurven und Formen definiert. |
| EmfPlusDrawPath | `16405` | Der Datensatz definiert die Stiftstriche zum Zeichnen der Figuren in einem Grafikpfad. Ein Pfad ist ein Objekt, das eine beliebige Folge von Linien, Kurven und Formen definiert. |
| EmfPlusFillClosedCurve | `16406` | Dieser Datensatz definiert, wie das Innere eines geschlossenen Kardinal-Splines mit einem bestimmten Pinsel gefüllt wird. |
| EmfPlusDrawClosedCurve | `16407` | Dieser Datensatz definiert den Stift und die Striche zum Zeichnen eines geschlossenen Kardinal-Splines. |
| EmfPlusDrawCurve | `16408` | Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Kardinal-Splines. |
| EmfPlusDrawBeziers | `16409` | Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Bezier-Splines. |
| EmfPlusDrawImage | `16410` | Dieser Datensatz definiert eine skalierte[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)Objekt (Abschnitt 2.2.1.4). Ein Bild kann entweder aus Bitmap- oder Metafile-Daten bestehen. |
| EmfPlusDrawImagePoints | `16411` | Dieser Datensatz definiert ein skaliertes EmfPlusImage-Objekt innerhalb eines Parallelogramms. Ein Bild kann entweder aus Bitmap- oder Metafile-Daten bestehen. |
| EmfPlusDrawString | `16412` | Dieser Datensatz definiert eine Textzeichenfolge basierend auf einer Schriftart, einem Layoutrechteck und einem Format. |
| EmfPlusSetRenderingOrigin | `16413` | Dieser Datensatz definiert den Rendering-Ursprung zu den angegebenen horizontalen und vertikalen Koordinaten. Dies gilt für Schraffurpinsel und Dither-Muster mit 8 und 16 Bit pro Pixel. |
| EmfPlusSetAntiAliasMode | `16414` | Dieser Datensatz definiert, ob Text-Anti-Aliasing aktiviert oder deaktiviert wird. Text-Anti-Aliasing ist eine Methode, um Linien und Kanten von Zeichen-Glyphen glatter erscheinen zu lassen, wenn sie auf einer Ausgabeoberfläche gezeichnet werden. |
| EmfPlusSetTextRenderingHint | `16415` | Dieser Datensatz definiert den Prozess, der zum Rendern von Text verwendet wird. |
| EmfPlusSetTextContrast | `16416` | Dieser Datensatz legt den Textkontrast gemäß dem angegebenen Text-Gammawert fest. |
| EmfPlusSetInterpolationMode | `16417` | Dieser Datensatz definiert den Interpolationsmodus eines Objekts gemäß der angegebenen Art der Bildfilterung. Der Interpolationsmodus beeinflusst, wie die Skalierung (Strecken und Schrumpfen) durchgeführt wird. |
| EmfPlusSetPixelOffsetMode | `16418` | Dieser Datensatz definiert den Pixel-Offset-Modus gemäß dem angegebenen Pixelzentrierungswert. |
| EmfPlusSetCompositingMode | `16419` | Dieser Datensatz definiert den Compositing-Modus gemäß dem Status von Alpha-Blending, der angibt, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| EmfPlusSetCompositingQuality | `16420` | Dieser Datensatz definiert die Compositing-Qualität, die das gewünschte Qualitätsniveau für die Erstellung zusammengesetzter Bilder aus mehreren Objekten beschreibt. |
| EmfPlusSave | `16421` | Dieser Datensatz speichert den Grafikstatus, identifiziert durch einen angegebenen Index, auf einem Stapel gespeicherter Grafikstatus. Jeder Stapelindex ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird von einem verwendet[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) record (Abschnitt 2.3.7.4) um den Zustand wiederherzustellen. |
| EmfPlusRestore | `16422` | Dieser Datensatz stellt den durch einen angegebenen Index identifizierten Grafikstatus aus einem Stapel gespeicherter Grafikstatus wieder her. Jeder Stack-Index ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird durch eine definiert[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) record (Abschnitt 2.3.7.5), um den Zustand zu speichern. |
| EmfPlusBeginContainer | `16423` | Dieser Datensatz öffnet einen neuen Grafikzustandscontainer und gibt eine Transformation dafür an. Grafikcontainer werden verwendet, um Elemente des Grafikstatus beizubehalten. |
| EmfPlusBeginContainerNoParams | `16424` | Dieser Datensatz öffnet einen neuen Grafikzustandscontainer. |
| EmfPlusEndContainer | `16425` | Dieser Datensatz schließt einen Grafikstatus-Container, der zuvor durch eine Container-Beginn-Operation geöffnet wurde. |
| EmfPlusSetWorldTransform | `16426` | Dieser Datensatz definiert die aktuelle Weltraumtransformation im Kontext des Wiedergabegeräts gemäß einer angegebenen Transformationsmatrix. |
| EmfPlusResetWorldTransform | `16427` | Dieser Datensatz setzt die aktuelle Weltraumtransformation auf die Identifizierungsmatrix zurück. |
| EmfPlusMultiplyWorldTransform | `16428` | Dieser Datensatz multipliziert den aktuellen Weltraum mit einer angegebenen Transformationsmatrix. |
| EmfPlusTranslateWorldTransform | `16429` | Dieser Datensatz wendet eine Translationstransformation auf den aktuellen Weltraum um bestimmte horizontale und vertikale Entfernungen an. |
| EmfPlusScaleWorldTransform | `16430` | Dieser Datensatz wendet eine Skalierungstransformation auf den aktuellen Weltraum durch angegebene horizontale und vertikale Skalierungsfaktoren an. |
| EmfPlusRotateWorldTransform | `16431` | Dieser Datensatz dreht den aktuellen Weltraum um einen bestimmten Winkel. |
| EmfPlusSetPageTransform | `16432` | Dieser Datensatz gibt zusätzliche Skalierungsfaktoren für die aktuelle Weltraumtransformation an. |
| EmfPlusResetClip | `16433` | Dieser Datensatz setzt den aktuellen Clipping-Bereich für den Weltraum auf unendlich zurück. |
| EmfPlusSetClipRect | `16434` | Dieser Datensatz kombiniert den aktuellen Clipping-Bereich mit einem Rechteck. |
| EmfPlusSetClipPath | `16435` | Dieser Datensatz kombiniert den aktuellen Clipping-Bereich mit einem Grafikpfad. |
| EmfPlusSetClipRegion | `16436` | Dieser Datensatz kombiniert den aktuellen Clipping-Bereich mit einem anderen Grafikbereich. |
| EmfPlusOffsetClip | `16437` | Dieser Datensatz wendet eine Übersetzungstransformation auf die aktuelle Clipping-Region des Weltraums an. |
| EmfPlusDrawDriverString | `16438` | Dieser Datensatz spezifiziert die Textausgabe mit Zeichenpositionen. |
| EmfPlusStrokeFillPath | `16439` | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, streicht den Umriss des Pfads mit dem aktuellen Stift und füllt sein Inneres mit dem aktuellen Pinsel. |
| EmfPlusSerializableObject | `16440` | Dieser Datensatz definiert einen Parameterblock für Bildeffekte, der in einen Datenpuffer serialisiert wurde. |
| EmfPlusSetTSGraphics | `16441` | Dieser Datensatz gibt den Status eines Grafikgerätekontexts für einen Terminalserver an. |
| EmfPlusSetTSClip | `16442` | Dieser Datensatz gibt Clipping-Bereiche im Grafikgerätekontext für einen Terminalserver an. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
