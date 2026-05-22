---
title: "EmfCreateBrushIndirect Classe"
type: docs
weight: 260
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

**Summary:** The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect__1) | Initialise une nouvelle instance de la classe [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/). |
| [EmfCreateBrushIndirect(source)](#EmfCreateBrushIndirect_source_2) | Initialise une nouvelle instance de la classe [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_brush | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet pinceau logique<br/>            dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être<br/>            réutilisé ou modifié. |
| log_brush | [EmfLogBrushEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/) | r/w | Obtient ou définit un objet LogBrushEx (section 2.2.12) qui spécifie le style, la couleur et<br/>            le motif du pinceau logique. Le champ BrushStyle de cet objet DOIT être BS_SOLID,<br/>            BS_HATCHED ou BS_NULL. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateBrushIndirect() {#EmfCreateBrushIndirect__1}


```
 EmfCreateBrushIndirect() 
```

Initialise une nouvelle instance de la classe [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/).

### Constructor: EmfCreateBrushIndirect(source) {#EmfCreateBrushIndirect_source_2}


```
 EmfCreateBrushIndirect(source) 
```

Initialise une nouvelle instance de la classe [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/).

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


