---
title: "EmfAlphaBlend Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Initialisiert eine neue Instanz der [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | Ruft ab oder legt fest ein WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8), das die Hintergrundfarbe der Quell‑Bitmap angibt. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Ruft ab oder legt fest eine Struktur, die die Mischvorgänge für Quell‑ und <br/>            Ziel‑Bitmaps definiert. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt fest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ziel‑Begrenzungsrechteck in Geräte‑Einheiten definiert. |
| cx_dest | int | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenbehafteter Integer, der die logische Breite des Ziel‑<br/>            Rechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| cx_src | int | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenbehafteter Integer, der die logische Breite des Quell‑Rechtecks angibt. <br/>            Dieser Wert MUSS größer als Null sein. |
| cy_dest | int | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenbehafteter Integer, der die logische Höhe des Ziel‑<br/>            Rechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| cy_src | int | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenbehafteter Integer, der die logische Höhe des Quell‑<br/>            Rechtecks angibt. Dieser Wert MUSS größer als Null sein. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ruft ab oder legt fest einen Puffer, der die Quell‑Bitmap enthält und nicht zwingend <br/>            zusammenhängend mit dem festen Teil des EMR_ALPHABLEND‑Datensatzes sein muss. Dementsprechend sind Felder in diesem <br/>            Puffer, die mit "UndefinedSpace" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenloser Integer, der angibt, wie Werte in der <br/>            Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
| x_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| x_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein XForm‑Objekt (Abschnitt 2.2.28), das eine Transformation vom Weltraum‑ in den Seitenraum definiert, die auf das Quell‑Bitmap angewendet wird. |
| y_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| y_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Quellrechtecks angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Initialisiert eine neue Instanz der [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/) Klasse.

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


