---
title: "EmfModifyWorldTransform Classe"
type: docs
weight: 640
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---

**Summary:** The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space<br/>            transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfModifyWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform__1) | Initialise une nouvelle instance de la classe [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
| [EmfModifyWorldTransform(source)](#EmfModifyWorldTransform_source_2) | Initialise une nouvelle instance de la classe [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| modify_world_transform_mode | [EmfModifyWorldTransformMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment la<br/>            transformation spécifiée dans Xform est utilisée. Cette valeur DOIT appartenir à l'énumération<br/>            ModifyWorldTransformMode (section 2.1.24). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet XForm (section 2.2.28), qui définit une transformation de l'espace mondial à l'espace de la page. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfModifyWorldTransform() {#EmfModifyWorldTransform__1}


```
 EmfModifyWorldTransform() 
```

Initialise une nouvelle instance de la classe [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

### Constructor: EmfModifyWorldTransform(source) {#EmfModifyWorldTransform_source_2}


```
 EmfModifyWorldTransform(source) 
```

Initialise une nouvelle instance de la classe [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Le type d'enregistrement. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


