---
title: "EmfGlsBoundedRecord Classe"
type: docs
weight: 540
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---

**Summary:** The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsBoundedRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfGlsBoundedRecord(source)](#EmfGlsBoundedRecord_source_1) | Initialise une nouvelle instance de la classe [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit un rectangle englobant<br/>en unités de dispositif, pour la sortie produite par l'exécution de la fonction OpenGL. |
| cb_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data.<br/>            Si cette valeur est zéro, aucune donnée n'est attachée à cet enregistrement. |
| données | System.Byte | r/w | Obtient ou définit un tableau optionnel d'octets de longueur cbData qui spécifie les données pour la fonction OpenGL. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGlsBoundedRecord(source) {#EmfGlsBoundedRecord_source_1}


```
 EmfGlsBoundedRecord(source) 
```

Initialise une nouvelle instance de la classe [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/).

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


