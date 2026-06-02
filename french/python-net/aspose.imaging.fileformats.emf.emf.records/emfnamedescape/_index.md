---
title: "Classe EmfNamedEscape"
type: docs
weight: 660
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---

**Summary:** The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfNamedEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfNamedEscape(source)](#EmfNamedEscape_source_1) | Initialise une nouvelle instance de la classe [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_driver | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le champ <br/>            DriverName. Cette valeur DOIT être un nombre pair. |
| cj_in | int | r/w | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre d'octets à transmettre au pilote d'imprimante. |
| données | System.Byte | r/w | Obtient ou définit les données à transmettre au pilote d'imprimante. Il DOIT y avoir cjIn octets disponibles. |
| driver_name | string | r/w | Obtient ou définit une chaîne de caractères Unicode de 16 bits qui spécifie le nom du<br/>pilote d'imprimante qui recevra les données. Cette valeur DOIT avoir une longueur de cjDriver octets, et elle DOIT être<br/>terminée par un caractère nul. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l'échappement du pilote d'imprimante à <br/>            exécuter. Cela DOIT être l'une des valeurs de l'énumération WMF MetafileEscapes ([MSWMF] section 2.1.1.17). |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfNamedEscape(source) {#EmfNamedEscape_source_1}


```
 EmfNamedEscape(source) 
```

Initialise une nouvelle instance de la classe [EmfNamedEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/).

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


