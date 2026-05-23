---
title: "EmfPlusSerializableObject‑Klasse"
type: docs
weight: 440
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Puffer | System.Byte | r/w | Liest oder schreibt ein Array aus BufferSize‑Bytes, das den serialisierten Bild‑Effekt‑Parameterblock enthält, der der GUID im Feld ObjectGUID entspricht. Dieser MUSS eines der Bild‑Effekt‑Objekte sein (Abschnitt 2.2.3). |
| buffer_size | int | r/w | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Größe in Bytes des 32‑Bit‑ausgerichteten Buffer‑Feldes angibt. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder schreibt eine 16‑Bit‑vorzeichenlose Ganzzahl, die nicht verwendet wird. Dieses Feld SOLLTE auf Null gesetzt werden<br/> und MUSS bei Empfang ignoriert werden. |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | Liest oder schreibt den Bildeffekt. |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | Liest oder schreibt den GUID‑Paketdarstellungswert ([MS-DTYP] Abschnitt 2.3.4.2)<br/> für den Bildeffekt. Dieser MUSS einem der ImageEffects‑Bezeichner entsprechen (Abschnitt 2.1.3.1). |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

