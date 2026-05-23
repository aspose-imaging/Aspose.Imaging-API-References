---
title: "EmfPlusDrawDriverString Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Initialisiert eine neue Instanz der [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder setzt die Pinsel‑Kennung<br/>            Ein 32‑Bit vorzeichenloser Integer, der entweder die Vordergrundfarbe des Textes oder einen Grafikpinsel angibt,<br/>            abhängig vom Wert des S‑Flags im Flags‑Feld. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Liest oder setzt die Treiberzeichen‑Optionen‑Flags<br/>            Ein 32‑Bit vorzeichenloser Integer, der den Abstand, die Ausrichtung und die Renderqualität für die Zeichenkette angibt. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| glyph_count | int | r/w | Liest oder setzt die Glyphenanzahl<br/>            Ein 32‑Bit vorzeichenloser Integer, der die Anzahl der Glyphen in der Zeichenkette angibt. |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt das Glyph‑Positions‑Array<br/>            Ein Array von EmfPlusPointF‑Objekten (Abschnitt 2.2.2.36), die die Ausgabeposition jedes Zeichen‑Glyphen angeben.<br/>            Es MUSS GlyphCount‑Elemente geben, die eine Eins‑zu‑Eins‑Entsprechung zu den Elementen im Glyphs‑Array haben.<br/>            Glyph‑Positionen werden aus der Position des ersten Glyphen berechnet, wenn das DriverStringOptionsRealizedAdvance‑Flag<br/>            in den DriverStringOptions‑Flags gesetzt ist. In diesem Fall gibt GlyphPos nur die Position des ersten Glyphen an. |
| glyphs | int[] | r/w | Liest oder setzt das Glyph‑Array<br/>            Ein Array von 16‑Bit‑Werten, die die zu zeichnende Zeichenkette definieren.<br/>            Ist das DriverStringOptionsCmapLookup‑Flag im DriverStringOptionsFlags‑Feld gesetzt, gibt jeder Wert in diesem<br/>            Array ein Unicode‑Zeichen an. Andernfalls gibt jeder Wert einen Index zu einem<br/>            Zeichen‑Glyphen im EmfPlusFont‑Objekt an, das durch den ObjectId‑Wert im Flags‑Feld spezifiziert wird. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist.<br/>            Dieses Bit gibt den Datentyp im BrushId‑Feld an.<br/>            Ist es gesetzt, gibt BrushId den Farbwert in einem EmfPlusARGB‑Objekt an<br/>            (Abschnitt 2.2.2.1). Ist es nicht gesetzt, enthält BrushId den EMF+‑Objekttabellen‑Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1). |
| matrix_present | int | r/w | Liest oder setzt das Matrix‑vorhanden‑Flag<br/>            Ein 32‑Bit vorzeichenloser Integer, der angibt, ob eine Transformationsmatrix im TransformMatrix‑Feld vorhanden ist<br/>            0 – keine Matrix vorhanden. 1 – Transformationsmatrix ist im TransformMatrix‑Feld. |
| object_id | System.Byte | r/w | Liest oder setzt die Objekt‑Kennung.<br/>            Der EMF+‑Objekttabellen‑Index eines ***EmfPlusFont***‑Objekts (Abschnitt<br/>            2.2.1.3) zum Rendern des Textes. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt die Transformationsmatrix<br/>            Ein optionales EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die Transformation angibt, die auf<br/>            jeden Wert im Text‑Array angewendet werden soll. Das Vorhandensein dieser Daten wird anhand des MatrixPresent‑Feldes bestimmt. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Initialisiert eine neue Instanz der [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

