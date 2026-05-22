---
title: "Classe EmfPolyTextOutA"
type: docs
weight: 880
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---

**Summary:** The EMR_POLYTEXTOUTA record draws one or more ASCII text strings using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyTextOutA

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyTextOutA()](#EmfPolyTextOutA__1) | Initialise une nouvelle instance de la classe [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
| [EmfPolyTextOutA(source)](#EmfPolyTextOutA_source_2) | Initialise une nouvelle instance de la classe [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_emr_text | [EmfText[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Obtient ou définit un tableau d'objets EmrText (section 2.2.5) qui spécifient les chaînes de sortie <br/>            en caractères ASCII 8 bits, avec des attributs de texte et des valeurs d'espacement. Le nombre d' <br/>            objets EmrText est indiqué par cStrings. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19), qui spécifie le <br/>            rectangle englobant en unités de dispositif. |
| ex_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle X des unités de page vers les unités de .01 mm si le mode graphique est GM_COMPATIBLE. |
| ey_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie l'échelle Y des unités de page vers les unités de .01 mm si le mode graphique est GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique actuel, <br/>            provenant de l'énumération GraphicsMode (section 2.1.16). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyTextOutA() {#EmfPolyTextOutA__1}


```
 EmfPolyTextOutA() 
```

Initialise une nouvelle instance de la classe [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

### Constructor: EmfPolyTextOutA(source) {#EmfPolyTextOutA_source_2}


```
 EmfPolyTextOutA(source) 
```

Initialise une nouvelle instance de la classe [EmfPolyTextOutA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/).

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


