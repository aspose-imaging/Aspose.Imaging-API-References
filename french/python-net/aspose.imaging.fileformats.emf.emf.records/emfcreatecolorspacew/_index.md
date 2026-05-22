---
title: "EmfCreateColorSpaceW Class"
type: docs
weight: 280
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

**Summary:** The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateColorSpaceW(source)](#EmfCreateColorSpaceW_source_1) | Initialise une nouvelle instance de la classe [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| données | System.Byte | r/w | Obtient ou définit un tableau d’octets optionnel qui spécifie les données du profil couleur. |
| dw_flags | int | r/w | Obtient ou définit un entier non signé de 32 bits qui fournit des informations sur les données de cet enregistrement. |
| ih_cs | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'espace couleur logique<br/>            objet dans la table des objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet<br/>            puisse être réutilisé ou modifié. |
| lcs | [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | r/w | Obtient ou définit un objet WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12) qui peut spécifier<br/>            le nom d’un profil couleur en caractères Unicode UTF16-LE |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateColorSpaceW(source) {#EmfCreateColorSpaceW_source_1}


```
 EmfCreateColorSpaceW(source) 
```

Initialise une nouvelle instance de la classe [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/).

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


