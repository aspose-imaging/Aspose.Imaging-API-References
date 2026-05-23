---
title: "EmfPlusDrawString Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder setzt die Pinselkennung<br/>            Eine 32‑Bit‑Unsigned‑Integer, die den Pinsel angibt, dessen Inhalt<br/>            durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet<br/>            um die Vordergrund‑Textfarbe zu malen; das heißt, nur die Glyphen selbst. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| format_id | int | r/w | Liest oder setzt die Formatkennung<br/>            Eine 32‑Bit‑Unsigned‑Integer, die den Index eines optionalen<br/>            EmfPlusStringFormat‑Objekts (Abschnitt 2.2.1.9) in der EMF+‑Objekttabelle angibt.<br/>            Dieses Objekt gibt Textlayout‑Informationen und Anzeige­manipulationen an,<br/>            die auf einen String angewendet werden. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist.<br/>            Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an.<br/>            Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts<br/>            (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt das Layout‑Rechteck<br/>            Ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das den Begrenzungsbereich<br/>            des Ziels definiert, das den String empfangen wird. |
| length | int | r/w | Liest oder setzt die Länge<br/>            32‑Bit‑Unsigned‑Integer, der die Anzahl der Zeichen im String angibt. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusFont‑Objekts (Abschnitt 2.2.1.3) in der EMF+<br/>            Objekttabelle zum Rendern des Textes. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| string_data | string | r/w | Liest oder setzt die String‑Daten<br/>            Ein Array von 16‑Bit‑Unicode‑Zeichen, das den zu zeichnenden String angibt. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

