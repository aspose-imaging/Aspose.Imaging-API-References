---
title: "EmfCreatePen Classe"
type: docs
weight: 320
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---

**Summary:** The EMR_CREATEPEN record defines a logical pen for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreatePen()](#EmfCreatePen__1) | Initialise une nouvelle instance de la classe [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
| [EmfCreatePen(source)](#EmfCreatePen_source_2) | Initialise une nouvelle instance de la classe [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pen | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet stylo logique dans<br/>            la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être<br/>            réutilisé ou modifié. |
| log_pen | [EmfLogPen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpen/) | r/w | Obtient ou définit un objet LogPen (section 2.2.19) qui spécifie le style, la largeur et la couleur<br/>            du stylo logique. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePen() {#EmfCreatePen__1}


```
 EmfCreatePen() 
```

Initialise une nouvelle instance de la classe [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

### Constructor: EmfCreatePen(source) {#EmfCreatePen_source_2}


```
 EmfCreatePen(source) 
```

Initialise une nouvelle instance de la classe [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

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


