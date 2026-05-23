---
title: "EmfPlgBlt Klasse"
type: docs
weight: 750
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt ein Array von drei WMF‑PointL‑Objekten ([MS‑WMF] Abschnitt 2.2.2.15), das <br/>            drei Ecken eines Parallelogramms als Zielbereich für die Blockübertragung angibt.<br/>            Die obere linke Ecke des Quellrechtecks wird dem ersten Punkt in diesem Array zugeordnet, die <br/>            obere rechte Ecke dem zweiten Punkt und die untere linke Ecke dem dritten Punkt. Die untere rechte Ecke des Quellrechtecks wird dem impliziten vierten Punkt im <br/>            Parallelogramm zugeordnet, der aus den ersten drei Punkten (A, B und C) berechnet wird, indem sie als <br/>            Vektoren behandelt werden. <br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | Liest oder setzt ein WMF‑ColorRef‑Objekt ([MS‑WMF] Abschnitt 2.2.2.8), das die <br/>            Hintergrundfarbe der Quell‑Bitmap angibt. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF‑RectL‑Objekt ([MS‑WMF] Abschnitt 2.2.2.19), das das <br/>            begrenzende Rechteck in Geräte‑Einheiten für die Ausgabe zum Ziel definiert. |
| cx_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Quellrechtecks angibt. |
| cy_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Quellrechtecks angibt. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der das Masken‑Bitmap enthält, das nicht <br/> erforderlich ist, zusammenhängend mit dem festen Teil des EMR_PLGBLT‑Datensatzes oder miteinander zu sein. <br/> Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält, das nicht <br/> erforderlich ist, zusammenhängend mit dem festen Teil des EMR_PLGBLT‑Datensatzes oder miteinander zu sein. <br/> Dementsprechend sind Felder in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der <br/>            Farbpalette im Header des Masken‑Bitmaps zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung liegen. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der <br/> Farbpalette im Header des Quell‑Bitmaps zu interpretieren sind. Dieser Wert MÜSSEN in der DIBColors‑Aufzählung liegen. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein XForm‑Objekt (Abschnitt 2.2.28), das eine Transformation vom Weltraum‑ in den Seitenraum definiert, die auf das Quell‑Bitmap angewendet wird. |
| x_mask | int | r/w | Ruft einen 32‑Bit‑Vorzeichen‑Integer ab oder legt ihn fest, der die logische x‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| x_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
| y_mask | int | r/w | Ruft einen 32‑Bit‑Vorzeichen‑Integer ab oder legt ihn fest, der die logische y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| y_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Der Datensatztyp. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


