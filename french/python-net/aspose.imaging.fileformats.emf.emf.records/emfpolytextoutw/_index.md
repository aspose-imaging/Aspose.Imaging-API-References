---
title: "Classe EmfPolyTextOutW"
type: docs
weight: 890
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---

**Summary:** The EMR_POLYTEXTOUTW record draws one or more Unicode text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyTextOutW()](#EmfPolyTextOutW__1) | Initialise une nouvelle instance de la classe [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/). |
| [EmfPolyTextOutW(source)](#EmfPolyTextOutW_source_2) | Initialise une nouvelle instance de la classe [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le <br/>            rectangle englobant en unités de dispositif. |
| ex_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page vers les unités de .01 mm si le mode graphique est GM_COMPATIBLE. |
| ey_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page vers les unités de .01 mm si le mode graphique est GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, <br/>            provenant de l'énumération GraphicsMode (section 2.1.16). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| w_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie <br/>            en caractères Unicode UTF16-LE de 16 bits, avec des attributs de texte et des valeurs d'espacement. Le <br/>            nombre d'objets EmrText est indiqué par cStrings. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutW() {#EmfPolyTextOutW__1}


```
 EmfPolyTextOutW() 
```

Initialise une nouvelle instance de la classe [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/).

### Constructor: EmfPolyTextOutW(source) {#EmfPolyTextOutW_source_2}


```
 EmfPolyTextOutW(source) 
```

Initialise une nouvelle instance de la classe [EmfPolyTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/).

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


