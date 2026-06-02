---
title: "Classe EmfRestoreDc"
type: docs
weight: 1000
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

**Summary:** The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRestoreDc()](#EmfRestoreDc__1) | Initialise une nouvelle instance de la classe [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
| [EmfRestoreDc(source)](#EmfRestoreDc_source_2) | Initialise une nouvelle instance de la classe [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| saved_dc | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie l'état enregistré à restaurer par rapport à<br/>            l'état actuel. Cette valeur DOIT être négative ; –1 représente l'état le plus<br/>            récemment enregistré sur la pile, –2 celui d'avant, etc. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRestoreDc() {#EmfRestoreDc__1}


```
 EmfRestoreDc() 
```

Initialise une nouvelle instance de la classe [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

### Constructor: EmfRestoreDc(source) {#EmfRestoreDc_source_2}


```
 EmfRestoreDc(source) 
```

Initialise une nouvelle instance de la classe [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/).

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


