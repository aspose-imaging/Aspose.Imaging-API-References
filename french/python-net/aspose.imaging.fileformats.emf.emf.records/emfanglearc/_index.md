---
title: "EmfAngleArc Classe"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---

**Summary:** The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the <br/>            given radius and center. The length of the arc is defined by the given start and sweep angles

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAngleArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfAngleArc()](#EmfAngleArc__1) | Initialise une nouvelle instance de la classe [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) |
| [EmfAngleArc(source)](#EmfAngleArc_source_2) | Initialise une nouvelle instance de la classe [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits, spécifié dans [MS-WMF] section 2.2.2.15, qui <br/>            spécifie les coordonnées logiques du centre du cercle. |
| rayon | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le rayon du cercle, en unités logiques. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| start_angle | float | r/w | Obtient ou définit un flottant de 32 bits qui spécifie l'angle de départ de l'arc, en degrés. |
| sweep_angle | float | r/w | Obtient ou définit un flottant de 32 bits qui spécifie l'angle d'extension de l'arc, en degrés. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAngleArc() {#EmfAngleArc__1}


```
 EmfAngleArc() 
```

Initialise une nouvelle instance de la classe [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/)

### Constructor: EmfAngleArc(source) {#EmfAngleArc_source_2}


```
 EmfAngleArc(source) 
```

Initialise une nouvelle instance de la classe [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/)

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


