---
title: "EmfSmallTextOut Classe"
type: docs
weight: 1380
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Initialise une nouvelle instance de la classe [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL optionnel de 128 bits ([MS-WMF] section 2.2.2.19) qui<br/>spécifie le rectangle englobant en unités de dispositif. |
| c_chars | int | r/w | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre de caractères de 16 bits dans la<br/>chaîne. La chaîne n'est PAS terminée par un caractère nul. |
| ex_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction x. |
| ey_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d'échelle du texte dans la direction y. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Obtient ou définit un entier non signé de 32 bits spécifiant les options de sortie de texte à utiliser. Ces<br/>options sont spécifiées par une ou une combinaison de valeurs de l'énumération ExtTextOutOptions<br/>(section 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtient ou définit un entier non signé de 32 bits spécifiant le mode graphique, à partir de l'énumération<br/>GraphicsMode (section 2.1.16). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| text_string | string | r/w | Obtient ou définit une chaîne de longueur variable qui contient la chaîne de texte à dessiner, en codes de caractères de 8 bits ou de 16 bits, selon la valeur du champ fuOptions. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| x | int | r/w | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée x de l'emplacement de la chaîne. |
| y | int | r/w | Obtient ou définit un entier signé de 32 bits spécifiant la coordonnée y de l'emplacement de la chaîne. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Initialise une nouvelle instance de la classe [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/).

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


