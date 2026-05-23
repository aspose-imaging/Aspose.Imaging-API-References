---
title: "EmfMaskBlt Klasse"
type: docs
weight: 600
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | Initialisiert eine neue Instanz der Klasse [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Liest oder setzt ein WMF‑ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.2.8), das die <br/>            Hintergrundfarbe der Quell‑Bitmap angibt. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt fest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ziel‑Begrenzungsrechteck in Geräte‑Einheiten definiert. |
| cx_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Breite des Zielrechtecks angibt. |
| cy_dest | int | r/w | Liest oder setzt einen 32‑Bit‑signed‑Integer, der die logische Höhe des Zielrechtecks angibt. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der die Masken‑Bitmaps enthält, die nicht <br/>            zwingend zusammenhängend mit dem festen Teil des EMR_MASKBLT‑Datensatzes oder miteinander <br/>            sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und <br/>            MÜSSEN ignoriert werden. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | Liest oder setzt eine quartäre Rasteroperation, die ternäre Rasteroperationen für <br/>            Vorder‑ und Hintergrundfarben eines Bitmaps spezifiziert. Diese Werte definieren, wie die Farbdaten des <br/>            Quellrechtecks mit den Farbdaten des Zielrechtecks kombiniert werden. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der die Quell‑Bitmaps enthält, die nicht <br/>            zwingend zusammenhängend mit dem festen Teil des EMR_MASKBLT‑Datensatzes oder miteinander <br/>            sein müssen. Dementsprechend sind Felder in diesem Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und <br/>            MÜSSEN ignoriert werden. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die angibt, wie Werte in der <br/>            Farbpalette im Header des Masken‑Bitmaps zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung liegen. |
| usage_src | int | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenloser Integer, der angibt, wie Werte in der <br/>            Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
| x_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| x_mask | int | r/w | Ruft einen 32‑Bit‑Vorzeichen‑Integer ab oder legt ihn fest, der die logische x‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| x_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein XForm‑Objekt (Abschnitt 2.2.28), das eine Transformation vom Weltraum‑ in den Seitenraum definiert, die auf das Quell‑Bitmap angewendet wird. |
| y_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| y_mask | int | r/w | Ruft einen 32‑Bit‑Vorzeichen‑Integer ab oder legt ihn fest, der die logische y‑Koordinate der oberen linken Ecke der Masken‑Bitmap angibt. |
| y_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/).

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


