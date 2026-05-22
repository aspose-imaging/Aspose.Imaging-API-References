---
title: "Classe EmfColorMatchToTargetW"
type: docs
weight: 150
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---

**Summary:** The EMR_COLORMATCHTOTargetW record specifies whether to perform color matching with a color<br/>            profile that is specified in a file with a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorMatchToTargetW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorMatchToTargetW(source)](#EmfColorMatchToTargetW_source_1) | Initialise une nouvelle instance de la classe [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données brutes du profil couleur cible<br/>            si elles sont contenues dans le champ Data. |
| cb_name | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom Unicode<br/>            UTF16-LE du profil couleur souhaité. |
| données | System.Byte | r/w | Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE<br/>            et les données brutes du profil couleur souhaité. |
| dw_action | [EmfColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie une valeur de l'énumération ColorSpace<br/>            (section 2.1.7). |
| dw_flags | [EmfColorMatchToTarget](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcolormatchtotarget/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie une valeur de l'énumération<br/>            ColorMatchToTarget (section 2.1.6). |
| nom | string | r | Obtient le nom |
| raw_data | System.Byte | r | Obtient les données brutes |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfColorMatchToTargetW(source) {#EmfColorMatchToTargetW_source_1}


```
 EmfColorMatchToTargetW(source) 
```

Initialise une nouvelle instance de la classe [EmfColorMatchToTargetW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/).

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


