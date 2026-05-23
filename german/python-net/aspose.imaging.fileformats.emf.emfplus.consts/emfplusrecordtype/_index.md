---
title: "EmfPlusRecordType Aufzählung"
type: docs
weight: 360
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

Die RecordType-Aufzählung definiert Record-Typen, die in EMF+-Metadateien verwendet werden.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | Dieser Datensatz öffnet einen neuen Grafikzustands-Container und gibt eine Transformation dafür an. Grafikcontainer werden verwendet, um Elemente des Grafikzustands zu erhalten. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | Dieser Datensatz öffnet einen neuen Grafikzustands-Container. |
| EMF_PLUS_CLEAR | Dieser Datensatz löscht den Ausgabes <c>coordinate space</c> und initialisiert ihn mit einer angegebenen Hintergrundfarbe und Transparenz. |
| EMF_PLUS_COMMENT | Dieser Datensatz gibt beliebige private Daten an. |
| EMF_PLUS_DRAW_ARC | Der Datensatz definiert Stiftstriche zum Zeichnen eines Bogens einer Ellipse. |
| EMF_PLUS_DRAW_BEZIERS | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Bézier-Kurve. |
| EMF_PLUS_DRAW_CLOSED_CURVE | Dieser Datensatz definiert Stift und Striche zum Zeichnen einer geschlossenen Kardinalkurve. |
| EMF_PLUS_DRAW_CURVE | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Kardinalkurve. |
| EMF_PLUS_DRAW_DRIVER_STRING | Dieser Datensatz gibt die Textausgabe mit Zeichenpositionen an. |
| EMF_PLUS_DRAW_ELLIPSE | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Ellipse. |
| EMF_PLUS_DRAW_IMAGE | Dieser Datensatz definiert ein skaliertes [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) Objekt (Abschnitt 2.2.1.4). Ein Bild kann aus Bitmap- oder Metadatei-Daten bestehen. |
| EMF_PLUS_DRAW_IMAGE_POINTS | Dieser Datensatz definiert ein skaliertes EmfPlusImage-Objekt innerhalb eines Parallelogramms. Ein Bild kann aus Bitmap- oder Metadatei-Daten bestehen. |
| EMF_PLUS_DRAW_LINES | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe verbundener Linien. |
| EMF_PLUS_DRAW_PATH | Der Datensatz definiert die Stiftstriche, um die Figuren in einem Grafikpfad zu zeichnen. Ein Pfad ist ein Objekt, das eine beliebige Sequenz von Linien, Kurven und Formen definiert. |
| EMF_PLUS_DRAW_PIE | Dieser Datensatz definiert Stiftstriche zum Zeichnen eines Abschnitts einer Ellipse. |
| EMF_PLUS_DRAW_RECTS | Dieser Datensatz definiert die Stiftstriche zum Zeichnen einer Reihe von Rechtecken. |
| EMF_PLUS_DRAW_STRING | Dieser Datensatz definiert eine Textzeichenfolge basierend auf einer Schriftart, einem Layoutrechteck und einem Format. |
| EMF_PLUS_END_CONTAINER | Dieser Datensatz schließt einen Grafikzustandscontainer, der zuvor durch eine Begin-Container-Operation geöffnet wurde. |
| EMF_PLUS_END_OF_FILE | Dieser Datensatz gibt das Ende der EMF+-Daten in der Metadatei an. |
| EMF_PLUS_FILL_CLOSED_CURVE | Dieser Datensatz definiert, wie das Innere einer geschlossenen Kardinalspline mit einem angegebenen Pinsel gefüllt wird. |
| EMF_PLUS_FILL_ELLIPSE | Dieser Datensatz definiert, wie das Innere einer Ellipse mit einem angegebenen Pinsel gefüllt wird. |
| EMF_PLUS_FILL_PATH | Der Datensatz definiert, wie die Innenbereiche der in einem Grafikpfad definierten Figuren mit einem angegebenen Pinsel gefüllt werden. Ein Pfad ist ein Objekt, das eine beliebige Sequenz von Linien, Kurven und Formen definiert. |
| EMF_PLUS_FILL_PIE | Dieser Datensatz definiert, wie ein Abschnitt eines inneren Bereichs einer Ellipse mit einem angegebenen Pinsel gefüllt wird. |
| EMF_PLUS_FILL_POLYGON | Dieser Datensatz definiert die Daten zum Füllen des Inneren eines Polygons mit einem angegebenen Pinsel. |
| EMF_PLUS_FILL_RECTS | Dieser Datensatz definiert, wie die Innenbereiche einer Reihe von Rechtecken mit einem angegebenen Pinsel gefüllt werden. |
| EMF_PLUS_FILL_REGION | Dieser Datensatz definiert, wie das Innere einer Region mit einem angegebenen Pinsel gefüllt wird. |
| EMF_PLUS_GET_DC | Dieser Datensatz gibt an, dass nachfolgende EMF‑Datensätze, die in der Metadatei gefunden werden, VERARBEITET WERDEN SOLLTEN. EMF‑Datensätze werden nicht mehr verarbeitet, wenn der nächste EMF+‑Datensatz gefunden wird. |
| EMF_PLUS_HEADER | Dieser Datensatz gibt den Beginn der EMF+‑Daten in der Metadatei an. Er MUSS im ersten EMF‑Datensatz nach dem [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/)‑Datensatz ([MS-EMF] Abschnitt 2.3.4.2 Datensatz) eingebettet sein. |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | Dieser Datensatz multipliziert den aktuellen Weltkoordinatenraum mit einer angegebenen Transformationsmatrix. |
| EMF_PLUS_MULTI_FORMAT_END | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EMF_PLUS_MULTI_FORMAT_SECTION | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EMF_PLUS_MULTI_FORMAT_START | Dieser Datensatz ist reserviert und DARF NICHT verwendet werden. |
| EMF_PLUS_OBJECT | Dieser Datensatz gibt ein Objekt an, das in Grafikoperationen verwendet wird. |
| EMF_PLUS_OFFSET_CLIP | Dieser Datensatz wendet eine Translations‑Transformation auf die aktuelle Clipping‑Region des Weltkoordinatenraums an. |
| EMF_PLUS_RESET_CLIP | Dieser Datensatz setzt die aktuelle Clipping‑Region des Weltkoordinatenraums auf unendlich zurück. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | Dieser Datensatz setzt die aktuelle Weltkoordinatenraum‑Transformation auf die Identitätsmatrix zurück. |
| EMF_PLUS_RESTORE | Dieser Datensatz stellt den Grafikstatus, der durch einen angegebenen Index identifiziert wird, aus einem Stapel gespeicherter Grafikzustände wieder her. Jeder Stapel‑Index ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird durch einen [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/)‑Datensatz (Abschnitt 2.3.7.5) definiert, um den Zustand zu speichern. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | Dieser Datensatz rotiert den aktuellen Weltkoordinatenraum um einen angegebenen Winkel. |
| EMF_PLUS_SAVE | Dieser Datensatz speichert den Grafikstatus, der durch einen angegebenen Index identifiziert wird, in einem Stapel gespeicherter Grafikzustände. Jeder Stapel‑Index ist einem bestimmten gespeicherten Zustand zugeordnet, und der Index wird von einem [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/)‑Datensatz (Abschnitt 2.3.7.4) verwendet, um den Zustand wiederherzustellen. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | Dieser Datensatz wendet eine Skalierungs‑Transformation auf den aktuellen Weltkoordinatenraum mit angegebenen horizontalen und vertikalen Skalierungsfaktoren an. |
| EMF_PLUS_SERIALIZABLE_OBJECT | Dieser Datensatz definiert einen Bild-Effekte-Parameterblock, der in einen Datenpuffer serialisiert wurde. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | Dieser Datensatz definiert, ob die Text-Antialiasing aktiviert oder deaktiviert wird. Text-Antialiasing ist eine Methode, um Linien und Kanten von Zeichen‑glyphen beim Zeichnen auf einer Ausgabefläche glatter erscheinen zu lassen. |
| EMF_PLUS_SET_CLIP_PATH | Dieser Datensatz kombiniert die aktuelle Clipping-Region mit einem Grafikpfad. |
| EMF_PLUS_SET_CLIP_RECT | Dieser Datensatz kombiniert die aktuelle Clipping-Region mit einem Rechteck. |
| EMF_PLUS_SET_CLIP_REGION | Dieser Datensatz kombiniert die aktuelle Clipping-Region mit einer anderen Grafikregion. |
| EMF_PLUS_SET_COMPOSITING_MODE | Dieser Datensatz definiert den Kompositionsmodus gemäß dem Zustand des Alpha‑Blending, der festlegt, wie Quellfarben mit Hintergrundfarben kombiniert werden. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | Dieser Datensatz definiert die Kompositionsqualität, die das gewünschte Qualitätsniveau für die Erstellung zusammengesetzter Bilder aus mehreren Objekten beschreibt. |
| EMF_PLUS_SET_INTERPOLATION_MODE | Dieser Datensatz definiert den Interpolationsmodus eines Objekts gemäß dem angegebenen Bildfiltertyp. Der Interpolationsmodus beeinflusst, wie die Skalierung (Dehnung und Verkleinerung) durchgeführt wird. |
| EMF_PLUS_SET_PAGE_TRANSFORM | Dieser Datensatz gibt zusätzliche Skalierungsfaktoren für die aktuelle Weltkoordinaten‑Transformation an. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | Dieser Datensatz definiert den Pixelversatzmodus gemäß dem angegebenen Pixelzentrierungswert. |
| EMF_PLUS_SET_RENDERING_ORIGIN | Dieser Datensatz definiert den Ursprung des Renderns zu den angegebenen horizontalen und vertikalen Koordinaten. Dies gilt für Schraffurpinsel sowie für 8‑ und 16‑Bit‑pro‑Pixel‑Dither‑Muster. |
| EMF_PLUS_SET_TEXT_CONTRAST | Dieser Datensatz legt den Textkontrast gemäß dem angegebenen Text‑Gamma‑Wert fest. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | Dieser Datensatz definiert den für das Rendern von Text verwendeten Prozess. |
| EMF_PLUS_SET_TS_CLIP | Dieser Datensatz gibt die Clipping‑Bereiche im Grafikgerätekontext für einen Terminal‑Server an. |
| EMF_PLUS_SET_TS_GRAPHICS | Dieser Datensatz gibt den Zustand des Grafikgerätekontexts für einen Terminal‑Server an. |
| EMF_PLUS_SET_WORLD_TRANSFORM | Dieser Datensatz definiert die aktuelle Weltraum‑Transformation im Wiedergabe‑device_context gemäß einer angegebenen Transformationsmatrix. |
| EMF_PLUS_STROKE_FILL_PATH | Dieser Datensatz schließt alle offenen Figuren in einem Pfad, zeichnet die Kontur des Pfads mit dem aktuellen Stift nach und füllt das Innere mit dem aktuellen Pinsel. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | Dieser Datensatz wendet eine Translations‑Transformation auf den aktuellen Weltraum an, basierend auf angegebenen horizontalen und vertikalen Abständen. |
