---
title: "EmfModifyWorldTransform‑klass"
type: docs
weight: 640
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---

**Summary:** The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space<br/>            transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfModifyWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform__1) | Initierar en ny instans av klassen [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
| [EmfModifyWorldTransform(source)](#EmfModifyWorldTransform_source_2) | Initierar en ny instans av klassen [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| modify_world_transform_mode | [EmfModifyWorldTransformMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar hur<br/>            transformen som anges i Xform används. Detta värde MÅSTE finnas i<br/>            enumen ModifyWorldTransformMode (avsnitt 2.1.24). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28), som definierar en världsrums‑till‑sidrymd‑transform. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfModifyWorldTransform() {#EmfModifyWorldTransform__1}


```
 EmfModifyWorldTransform() 
```

Initierar en ny instans av klassen [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

### Constructor: EmfModifyWorldTransform(source) {#EmfModifyWorldTransform_source_2}


```
 EmfModifyWorldTransform(source) 
```

Initierar en ny instans av klassen [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Posttypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


