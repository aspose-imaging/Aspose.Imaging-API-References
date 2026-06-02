---
title: "Classe EmfExtTextOutW"
type: docs
weight: 480
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---

**Summary:** The EMR_EXTTEXTOUTW record draws an ASCII text string using the current font and text colors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtTextOutW

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfExtTextOutW()](#EmfExtTextOutW__1) | Initialise une nouvelle instance de la classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
| [EmfExtTextOutW(source)](#EmfExtTextOutW_source_2) | Initialise une nouvelle instance de la classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19). Il n’est pas utilisé et <br/>            DOIT être ignoré à la réception. |
| ex_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d’échelle à appliquer le long de <br/>            l’axe X pour convertir les unités d’espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le <br/>            mode graphique spécifié par iGraphicsMode est GM_COMPATIBLE. |
| ey_scale | float | r/w | Obtient ou définit une valeur flottante de 32 bits qui spécifie le facteur d’échelle à appliquer le long de <br/>            l’axe Y pour convertir les unités d’espace de page en unités de 0,01 mm. Cela DOIT être utilisé uniquement si le <br/>            mode graphique spécifié par iGraphicsMode est GM_COMPATIBLE. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode graphique à partir de l’énumération <br/>            GraphicsMode (section 2.1.16). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| w_emr_text | [EmfText](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftext/) | r/w | Obtient ou définit un objet EmrText (section 2.2.5) qui spécifie la chaîne de sortie en caractères Unicode UTF16-LE sur 16 bits, avec des attributs de texte et des valeurs d'espacement. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtTextOutW() {#EmfExtTextOutW__1}


```
 EmfExtTextOutW() 
```

Initialise une nouvelle instance de la classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

### Constructor: EmfExtTextOutW(source) {#EmfExtTextOutW_source_2}


```
 EmfExtTextOutW(source) 
```

Initialise une nouvelle instance de la classe [EmfExtTextOutW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/).

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


