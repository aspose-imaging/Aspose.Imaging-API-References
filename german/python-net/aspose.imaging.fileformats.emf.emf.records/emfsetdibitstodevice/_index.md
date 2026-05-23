---
title: "EmfSetDiBitsToDevice Klasse"
type: docs
weight: 1150
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

**Summary:** The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSetDiBitsToDevice(source)](#EmfSetDiBitsToDevice_source_1) | Initialisiert eine neue Instanz der [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt fest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Ziel‑Begrenzungsrechteck in Geräte‑Einheiten definiert. |
| c_scans | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Scan‑Zeilen angibt. |
| cx_src | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die Breite in Pixeln des Quellrechtecks angibt. |
| cy_src | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die Höhe in Pixeln des Quellrechtecks angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der das Quell‑Bitmap enthält, das nicht erforderlich ist, <br/>            zusammenhängend mit dem festen Teil des EMR_SETDIBITSTODEVICE‑Datensatzes zu sein. Dementsprechend sind Felder <br/>            in diesem Puffer, die mit \"UndefinedSpace\" gekennzeichnet sind, optional und MÜSSEN ignoriert werden. |
| start_scan | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die erste Scan‑Zeile im Array angibt. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ruft ab oder legt fest ein 32‑Bit vorzeichenloser Integer, der angibt, wie Werte in der <br/>            Farbtafel im Header der Quell‑Bitmap zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
| x_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische x‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| x_src | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die x‑Koordinate in Pixeln der unteren linken <br/>            Ecke des Quellrechtecks angibt. |
| y_dest | int | r/w | Liest oder setzt einen 32‑Bit vorzeichenbehafteten Integer, der die logische y‑Koordinate der oberen linken <br/>            Ecke des Zielrechtecks angibt. |
| y_src | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die die y‑Koordinate in Pixeln der unteren linken <br/>            Ecke des Quellrechtecks angibt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSetDiBitsToDevice(source) {#EmfSetDiBitsToDevice_source_1}


```
 EmfSetDiBitsToDevice(source) 
```

Initialisiert eine neue Instanz der [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/) Klasse.

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


