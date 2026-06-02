---
title: "EmfGradientFill Classe"
type: docs
weight: 560
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---

**Summary:** The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGradientFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfGradientFill(source)](#EmfGradientFill_source_1) | Initialise une nouvelle instance de la classe [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui spécifie un <br/>            rectangle englobant, en unités de dispositif inclusives-inclusives. |
| n_tri | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de rectangles ou de triangles à remplir. |
| n_ver | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre de sommets. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| ul_mode | [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgradientfill/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode de remplissage en dégradé. La valeur <br/>            DOIT être dans l'énumération GradientFill (section 2.1.15). |
| vertex_data | [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | r/w | Obtient ou définit des objets qui spécifient les sommets de rectangles ou de triangles et <br/>            les couleurs qui leur correspondent. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGradientFill(source) {#EmfGradientFill_source_1}


```
 EmfGradientFill(source) 
```

Initialise une nouvelle instance de la classe [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/).

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


