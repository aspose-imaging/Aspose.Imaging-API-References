---
title: "Classe EmfSetIcmProfileA"
type: docs
weight: 1170
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---

**Summary:** The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII<br/>            characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileA

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetIcmProfileA(source)](#EmfSetIcmProfileA_source_1) | Initialise une nouvelle instance de la classe [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données du profil couleur, si elles<br/>            sont contenues dans le champ Data. |
| cb_name | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom ASCII<br/>            du profil couleur souhaité. |
| données | System.Byte | r/w | Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom ASCII<br/>            et les données brutes du profil couleur souhaité. |
| dw_flags | int | r/w | Obtient ou définit un entier non signé de 32 bits qui contient les indicateurs du profil couleur. |
| nom | string | r | Obtient le nom |
| raw_data | System.Byte | r | Obtient les données brutes |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetIcmProfileA(source) {#EmfSetIcmProfileA_source_1}


```
 EmfSetIcmProfileA(source) 
```

Initialise une nouvelle instance de la classe [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/).

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


