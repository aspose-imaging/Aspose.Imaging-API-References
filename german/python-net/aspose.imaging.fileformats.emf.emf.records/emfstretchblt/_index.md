---
title: "EmfStretchBlt Klasse"
type: docs
weight: 1400
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

**Summary:** The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfStretchBlt()](#EmfStretchBlt__1) | Initialisiert eine neue Instanz der [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) Klasse. |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_2) | Initialisiert eine neue Instanz der [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Liest oder setzt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die <br/>            Hintergrundfarbe der Quell‑Bitmap angibt. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Liest oder setzt einen 32‑Bit‑unsigned‑Integer, der den Rasteroperations‑<br/>            Code angibt. Dieser Code definiert, wie die Farbdaten des Quellrechtecks mit den <br/>            Farbdaten des Zielrechtecks und optional einem Pinsel‑Muster kombiniert werden, um die endgültige Farbe zu erhalten. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt fest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ziel‑Begrenzungsrechteck in Geräte‑Einheiten definiert. |
| cx_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Zielrechtecks angibt. |
| cx_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Quellrechtecks angibt. |
| cy_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Zielrechtecks angibt. |
| cy_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Quellrechtecks angibt. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt das Ziel‑Rechteck. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der die Quell‑Bitmap enthält, der nicht zusammenhängend mit dem festen Teil des EMR_STRETCHBLT‑Datensatzes sein muss. Dementsprechend sind Felder in diesem <br/>            Puffer, die als "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt das Quell‑Rechteck. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenloser Integer, der angibt, wie Werte in der <br/>            Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
| x_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| x_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein XForm‑Objekt (Abschnitt 2.2.28), das eine Transformation vom Weltraum‑ in den Seitenraum definiert, die auf das Quell‑Bitmap angewendet wird. |
| y_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| y_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

Initialisiert eine neue Instanz der [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) Klasse.

### Constructor: EmfStretchBlt(source) {#EmfStretchBlt_source_2}


```
 EmfStretchBlt(source) 
```

Initialisiert eine neue Instanz der [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/) Klasse.

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


