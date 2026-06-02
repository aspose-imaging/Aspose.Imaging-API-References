---
title: "EmfTransparentBlt Klasse"
type: docs
weight: 1450
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---

**Summary:** The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, treating a specified color as transparent, stretching or compressing the output <br/>            to fit the dimensions of the destination, if necessary

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfTransparentBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfTransparentBlt(source)](#EmfTransparentBlt_source_1) | Initialisiert eine neue Instanz der [EmfTransparentBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt fest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ziel‑Begrenzungsrechteck in Geräte‑Einheiten definiert. |
| cx_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Zielrechtecks angibt. |
| cx_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Quellrechtecks angibt. |
| cy_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Zielrechtecks angibt. |
| cy_src | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Quellrechtecks angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält und nicht zwingend <br/>            zusammenhängend mit dem festen Teil des EMR_TRANSPARENTBLT‑Datensatzes sein muss. Dementsprechend sind Felder in <br/>            diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| src_bk_argb_32_color | int | r/w | Liest oder setzt ein WMF‑ColorRef‑Objekt, das die Hintergrundfarbe des Quell‑Bitmaps angibt. |
| transparent_argb_32_color | int | r/w | Liest oder setzt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die Farbe im Quell‑Bitmap angibt, die als transparent behandelt werden soll. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der <br/>            Farbtafel im Header des Quell‑Bitmaps zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
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


### Constructor: EmfTransparentBlt(source) {#EmfTransparentBlt_source_1}


```
 EmfTransparentBlt(source) 
```

Initialisiert eine neue Instanz der [EmfTransparentBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/) Klasse.

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


