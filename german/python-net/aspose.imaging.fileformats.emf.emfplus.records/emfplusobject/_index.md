---
title: "EmfPlusObject Klasse"
type: docs
weight: 330
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_continuable | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz fortsetzbar ist.<br/>            Gibt an, dass die Objektdefinition im nächsten EmfPlusObject‑Datensatz fortgesetzt wird.<br/>            Dieses Flag wird niemals im letzten Datensatz gesetzt, der das Objekt definiert. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Liest oder setzt ein Byte‑Array, das Daten für den im Feld Flags angegebenen Objekttyp enthält.<br/>            Inhalt und Format der Daten können je nach Objekttyp variieren. Siehe die einzelnen Objektdefinitionen im Abschnitt 2.2.1 für weitere Informationen. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index in der EMF+ Objekt‑Tabelle, der dem durch diesen Datensatz erstellten Objekt zugeordnet wird.<br/>            Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Liest oder setzt den Typ des Objekts. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| total_object_size | int | r/w | Liest oder setzt die Gesamgröße des Objekts.<br/>            Wenn der Datensatz fortsetzbar ist und das Weiter‑Bit gesetzt ist, ist dieses Feld vorhanden.<br/>            Fortsetzende Objekte bestehen aus mehreren EMF+-Datensätzen, beginnend mit EmfPlusContineudObjectRecord.<br/>            Jeder EmfPlusContinuedObjectRecord enthält eine TotalObjectSize. Sobald die angegebene Anzahl von Bytes gemäß TotalObjectSize gelesen wurde, wird der nächste EMF+-Datensatz nicht mehr als Teil des fortsetzenden Objekts behandelt. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

