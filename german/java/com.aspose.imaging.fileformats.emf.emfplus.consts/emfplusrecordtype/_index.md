---
title: "EmfPlusRecordType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung RecordType definiert Aufzeichnungstypen, die in EMF-Metadateien verwendet werden."
type: docs
weight: 45
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

Die RecordType-Aufzählung definiert Aufzeichnungstypen, die in EMF+-Metadateien verwendet werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Dieser Datensatz gibt den Beginn der EMF+-Daten in der Metadatei an. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Dieser Datensatz gibt das Ende der EMF+-Daten in der Metadatei an. |
| [EmfPlusComment](#EmfPlusComment) | Dieser Datensatz gibt beliebige private Daten an. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Dieser Datensatz gibt an, dass nachfolgende EMF-Datensätze, die in der Metadatei gefunden werden, verarbeitet werden sollen. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Dieser Datensatz ist reserviert und darf nicht verwendet werden. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Dieser Datensatz ist reserviert und darf nicht verwendet werden. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Dieser Datensatz ist reserviert und darf nicht verwendet werden. |
| [EmfPlusObject](#EmfPlusObject) | Dieser Datensatz gibt ein Objekt für die Verwendung in Grafikoperationen an. |
| [EmfPlusClear](#EmfPlusClear) | Dieser Datensatz löscht die Ausgabe-`coordinate space` und initialisiert sie mit einer angegebenen Hintergrundfarbe und Transparenz. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Dieser Datensatz definiert, wie die Innenflächen einer Reihe von Rechtecken mit einem angegebenen Pinsel gefüllt werden. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe von Rechtecken. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Dieser Datensatz definiert die Daten zum Füllen des Inneren eines Polygons mit einem angegebenen Pinsel. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe verbundener Linien. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Dieser Datensatz definiert, wie die Innenflächen einer Ellipse mit einem angegebenen Pinsel gefüllt werden. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Ellipse. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Dieser Datensatz definiert, wie ein Abschnitt eines inneren Abschnitts einer Ellipse mit einem angegebenen Pinsel gefüllt wird. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Dieser Datensatz definiert Stiftstriche zum Zeichnen eines Abschnitts einer Ellipse. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | Der Datensatz definiert Stiftstriche zum Zeichnen eines Bogens einer Ellipse. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Dieser Datensatz definiert, wie das Innere einer Region mit einem angegebenen Pinsel gefüllt wird. |
| [EmfPlusFillPath](#EmfPlusFillPath) | Der Datensatz definiert, wie die Innenbereiche der in einem Grafikpfad definierten Figuren mit einem angegebenen Pinsel gefüllt werden. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | Der Datensatz definiert die Stiftstriche zum Zeichnen der Figuren in einem Grafikpfad. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Dieser Datensatz definiert, wie das Innere eines geschlossenen Kardinalsplines mit einem angegebenen Pinsel gefüllt wird. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Dieser Datensatz definiert den Stift und die Striche zum Zeichnen eines geschlossenen Kardinalsplines. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Kardinalsplines. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Bézier-Splines. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Dieser Datensatz definiert ein skaliertes [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)-Objekt (Abschnitt 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Dieser Datensatz definiert ein skaliertes EmfPlusImage-Objekt innerhalb eines Parallelogramms. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Dieser Datensatz definiert eine Textzeichenfolge basierend auf einer Schriftart, einem Layoutrechteck und einem Format. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Dieser Datensatz definiert den Ursprung des Renderns zu den angegebenen horizontalen und vertikalen Koordinaten. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Dieser Datensatz definiert, ob Text-Antialiasing aktiviert oder deaktiviert wird. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Dieser Datensatz definiert den für das Rendern von Text verwendeten Prozess. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Dieser Datensatz setzt den Textkontrast gemäß dem angegebenen Text-Gamma-Wert. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Dieser Datensatz definiert den Interpolationsmodus eines Objekts gemäß dem angegebenen Bildfiltertyp. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Dieser Datensatz definiert den Pixelversatzmodus gemäß dem angegebenen Pixelzentrierungswert. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Dieser Datensatz definiert den Kompositmodus gemäß dem Zustand des Alpha-Blending, der festlegt, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Dieser Datensatz definiert die Kompositqualität, die das gewünschte Qualitätsniveau für die Erstellung zusammengesetzter Bilder aus mehreren Objekten beschreibt. |
| [EmfPlusSave](#EmfPlusSave) | Dieser Datensatz speichert den Grafikzustand, identifiziert durch einen angegebenen Index, auf einem Stapel gespeicherter Grafikzustände. |
| [EmfPlusRestore](#EmfPlusRestore) | Dieser Datensatz stellt den Grafikzustand, identifiziert durch einen angegebenen Index, von einem Stapel gespeicherter Grafikzustände wieder her. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Dieser Datensatz öffnet einen neuen Grafikzustandscontainer und legt eine Transformation dafür fest. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Dieser Datensatz öffnet einen neuen Grafikzustandscontainer. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Dieser Datensatz schließt einen Grafikzustandscontainer, der zuvor durch eine Begin-Container-Operation geöffnet wurde. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Dieser Datensatz definiert die aktuelle Weltraum-Transformation im playback device\_context gemäß einer angegebenen Transformationsmatrix. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Dieser Datensatz setzt die aktuelle Weltraum-Transformation auf die Identitätsmatrix zurück. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Dieser Datensatz multipliziert den aktuellen Weltraum mit einer angegebenen Transformationsmatrix. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Dieser Datensatz wendet eine Translations‑Transformation auf den aktuellen Weltraum an, basierend auf angegebenen horizontalen und vertikalen Abständen. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Dieser Datensatz wendet eine Skalierungs‑Transformation auf den aktuellen Weltraum an, basierend auf angegebenen horizontalen und vertikalen Skalierungsfaktoren. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Dieser Datensatz rotiert den aktuellen Weltraum um einen angegebenen Winkel. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Dieser Datensatz gibt zusätzliche Skalierungsfaktoren für die aktuelle Weltraum-Transformation an. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Dieser Datensatz setzt die aktuelle Clipping‑Region für den Weltraum auf unendlich zurück. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einem Rechteck. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einem Grafikpfad. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einer anderen Grafikregion. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Dieser Datensatz wendet eine Translations‑Transformation auf die aktuelle Clipping‑Region des Weltraums an. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Dieser Datensatz gibt die Textausgabe mit Zeichenpositionen an. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfades mit dem aktuellen Stift und füllt das Innere mit dem aktuellen Pinsel. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Dieser Datensatz definiert einen Bild‑Effekt‑Parameterblock, der in einen Datenpuffer serialisiert wurde. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Dieser Datensatz gibt den Zustand eines Grafik‑Device‑Contexts für einen Terminal‑Server an. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Dieser Datensatz gibt Clipping‑Bereiche im Grafik‑Device‑Context für einen Terminal‑Server an. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Dieser Datensatz gibt den Beginn von EMF+-Daten in der Metadatei an. Er MUSS im ersten EMF‑Datensatz nach dem [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)‑Datensatz eingebettet sein ([MS-EMF] Abschnitt 2.3.4.2 Datensatz).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Dieser Datensatz gibt das Ende der EMF+-Daten in der Metadatei an.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Dieser Datensatz gibt beliebige private Daten an.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Dieser Datensatz gibt an, dass nachfolgende EMF‑Datensätze, die in der Metadatei gefunden werden, VERARBEITET WERDEN SOLLTEN. EMF‑Datensätze werden nicht mehr verarbeitet, wenn der nächste EMF+‑Datensatz gefunden wird.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Dieser Datensatz ist reserviert und darf nicht verwendet werden.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Dieser Datensatz ist reserviert und darf nicht verwendet werden.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Dieser Datensatz ist reserviert und darf nicht verwendet werden.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Dieser Datensatz gibt ein Objekt für die Verwendung in Grafikoperationen an.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Dieser Datensatz löscht die Ausgabe-`coordinate space` und initialisiert sie mit einer angegebenen Hintergrundfarbe und Transparenz.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Dieser Datensatz definiert, wie die Innenflächen einer Reihe von Rechtecken mit einem angegebenen Pinsel gefüllt werden.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe von Rechtecken.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Dieser Datensatz definiert die Daten zum Füllen des Inneren eines Polygons mit einem angegebenen Pinsel.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe verbundener Linien.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Dieser Datensatz definiert, wie die Innenflächen einer Ellipse mit einem angegebenen Pinsel gefüllt werden.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Ellipse.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Dieser Datensatz definiert, wie ein Abschnitt eines inneren Abschnitts einer Ellipse mit einem angegebenen Pinsel gefüllt wird.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Dieser Datensatz definiert Stiftstriche zum Zeichnen eines Abschnitts einer Ellipse.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


Der Datensatz definiert Stiftstriche zum Zeichnen eines Bogens einer Ellipse.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Dieser Datensatz definiert, wie das Innere einer Region mit einem angegebenen Pinsel gefüllt wird.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


Der Datensatz definiert, wie die Innenräume der in einem Grafikpfad definierten Figuren mit einem angegebenen Pinsel gefüllt werden. Ein Pfad ist ein Objekt, das eine beliebige Sequenz von Linien, Kurven und Formen definiert.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


Der Datensatz definiert die Stiftstriche zum Zeichnen der Figuren in einem Grafikpfad. Ein Pfad ist ein Objekt, das eine beliebige Sequenz von Linien, Kurven und Formen definiert.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Dieser Datensatz definiert, wie das Innere eines geschlossenen Kardinalsplines mit einem angegebenen Pinsel gefüllt wird.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Dieser Datensatz definiert den Stift und die Striche zum Zeichnen eines geschlossenen Kardinalsplines.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Kardinalsplines.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Dieser Datensatz definiert die Stiftstriche zum Zeichnen eines Bézier-Splines.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Dieser Datensatz definiert ein skaliertes [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)-Objekt (Abschnitt 2.2.1.4). Ein Bild kann aus Bitmap‑ oder Metadatei‑Daten bestehen.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Dieser Datensatz definiert ein skaliertes EmfPlusImage‑Objekt innerhalb eines Parallelogramms. Ein Bild kann aus Bitmap‑ oder Metadatei‑Daten bestehen.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Dieser Datensatz definiert eine Textzeichenfolge basierend auf einer Schriftart, einem Layoutrechteck und einem Format.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Dieser Datensatz definiert den Ursprung des Renderns zu den angegebenen horizontalen und vertikalen Koordinaten. Dies gilt für Schraffurpinsel und für 8‑ und 16‑Bit‑pro‑Pixel‑Dither‑Muster.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Dieser Datensatz definiert, ob Text‑Anti‑Aliasing aktiviert oder deaktiviert werden soll. Text‑Anti‑Aliasing ist eine Methode, um Linien und Kanten von Zeichen­glyphen beim Zeichnen auf einer Ausgabefläche glatter erscheinen zu lassen.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Dieser Datensatz definiert den für das Rendern von Text verwendeten Prozess.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Dieser Datensatz setzt den Textkontrast gemäß dem angegebenen Text-Gamma-Wert.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Dieser Datensatz definiert den Interpolationsmodus eines Objekts gemäß dem angegebenen Bildfiltertyp. Der Interpolationsmodus beeinflusst, wie die Skalierung (Dehnung und Verkleinerung) durchgeführt wird.

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Dieser Datensatz definiert den Pixelversatzmodus gemäß dem angegebenen Pixelzentrierungswert.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Dieser Datensatz definiert den Kompositmodus gemäß dem Zustand des Alpha-Blending, der festlegt, wie Quellfarben mit Hintergrundfarben kombiniert werden.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Dieser Datensatz definiert die Kompositqualität, die das gewünschte Qualitätsniveau für die Erstellung zusammengesetzter Bilder aus mehreren Objekten beschreibt.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Dieser Datensatz speichert den Grafikzustand, identifiziert durch einen angegebenen Index, auf einem Stapel gespeicherter Grafikzustände. Jeder Stapelindex ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird von einem [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore)-Datensatz (Abschnitt 2.3.7.4) verwendet, um den Zustand wiederherzustellen.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Dieser Datensatz stellt den Grafikzustand, identifiziert durch einen angegebenen Index, von einem Stapel gespeicherter Grafikzustände wieder her. Jeder Stapelindex ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird von einem [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave)-Datensatz (Abschnitt 2.3.7.5) definiert, um den Zustand zu speichern.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Dieser Datensatz öffnet einen neuen Grafikzustandscontainer und legt eine Transformation dafür fest. Grafikcontainer werden verwendet, um Elemente des Grafikzustands zu erhalten.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Dieser Datensatz öffnet einen neuen Grafikzustandscontainer.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Dieser Datensatz schließt einen Grafikzustandscontainer, der zuvor durch eine Begin-Container-Operation geöffnet wurde.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Dieser Datensatz definiert die aktuelle Weltraum-Transformation im playback device\_context gemäß einer angegebenen Transformationsmatrix.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Dieser Datensatz setzt die aktuelle Weltraum-Transformation auf die Identitätsmatrix zurück.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Dieser Datensatz multipliziert den aktuellen Weltraum mit einer angegebenen Transformationsmatrix.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Dieser Datensatz wendet eine Translations‑Transformation auf den aktuellen Weltraum an, basierend auf angegebenen horizontalen und vertikalen Abständen.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Dieser Datensatz wendet eine Skalierungs‑Transformation auf den aktuellen Weltraum an, basierend auf angegebenen horizontalen und vertikalen Skalierungsfaktoren.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Dieser Datensatz rotiert den aktuellen Weltraum um einen angegebenen Winkel.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Dieser Datensatz gibt zusätzliche Skalierungsfaktoren für die aktuelle Weltraum-Transformation an.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Dieser Datensatz setzt die aktuelle Clipping‑Region für den Weltraum auf unendlich zurück.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einem Rechteck.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einem Grafikpfad.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Dieser Datensatz kombiniert die aktuelle Clipping‑Region mit einer anderen Grafikregion.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Dieser Datensatz wendet eine Translations‑Transformation auf die aktuelle Clipping‑Region des Weltraums an.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Dieser Datensatz gibt die Textausgabe mit Zeichenpositionen an.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfades mit dem aktuellen Stift und füllt das Innere mit dem aktuellen Pinsel.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Dieser Datensatz definiert einen Bild‑Effekt‑Parameterblock, der in einen Datenpuffer serialisiert wurde.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Dieser Datensatz gibt den Zustand eines Grafik‑Device‑Contexts für einen Terminal‑Server an.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Dieser Datensatz gibt Clipping‑Bereiche im Grafik‑Device‑Context für einen Terminal‑Server an.

