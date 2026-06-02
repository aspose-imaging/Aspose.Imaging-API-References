---
title: "Classe EmfSetPixelV"
type: docs
weight: 1260
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---

**Summary:** The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPixelV

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetPixelV()](#EmfSetPixelV__1) | Initialise une nouvelle instance de la classe [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) . |
| [EmfSetPixelV(source)](#EmfSetPixelV_source_2) | Initialise une nouvelle instance de la classe [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie la couleur du pixel. |
| pixel | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un objet WMF PointL de 64 bits ([MS-WMF] section 2.2.2.15) qui spécifie les<br/>            coordonnées logiques du pixel. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetPixelV() {#EmfSetPixelV__1}


```
 EmfSetPixelV() 
```

Initialise une nouvelle instance de la classe [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) .

### Constructor: EmfSetPixelV(source) {#EmfSetPixelV_source_2}


```
 EmfSetPixelV(source) 
```

Initialise une nouvelle instance de la classe [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) .

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


