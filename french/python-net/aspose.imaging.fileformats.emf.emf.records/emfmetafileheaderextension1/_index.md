---
title: "EmfMetafileHeaderExtension1 Classe"
type: docs
weight: 620
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Obtient ou définit la description EMF<br/>            Une chaîne Unicode UTF16-LE optionnelle, terminée par un caractère nul, de longueur et de contenu arbitraires. <br/>            Son emplacement dans l'enregistrement et le nombre de caractères sont spécifiés par les champs offDescription <br/>            et nDescription, respectivement, dans EmfHeader. Si la valeur de l'un de ces champs <br/>            est zéro, aucune chaîne de description n'est présente. |
| emf_description_buffer | System.Byte | r/w | Obtient ou définit le tampon de description EMF<br/>            Un tableau d'octets optionnel qui contient la chaîne de description EMF, qui <br/>            n'est pas obligé d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeader. En conséquence, le champ de ce tampon nommé "UndefinedSpace" <br/>            est optionnel et DOIT être ignoré. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Obtient ou définit un objet Header (section 2.2.9), qui contient des informations sur le contenu<br/>            et la structure du métafichier |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Obtient ou définit un objet HeaderExtension1, qui spécifie des informations supplémentaires sur l'image dans le métafichier. |
| emf_header_record_buffer | System.Byte | r/w | Obtient ou définit un tableau d'octets optionnel qui contient le reste de l'enregistrement d'en-tête EMF. <br/>            La taille de ce champ DOIT être un multiple de 4 octets |
| emf_pixel_format_buffer | System.Byte | r/w | Obtient ou définit un tableau d'octets optionnel qui contient le descripteur de format de pixel EMF, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeaderExtension1 ou avec la chaîne de description EMF. En conséquence, le champ de ce tampon nommé "UndefinedSpace" est <br/>            optionnel et DOIT être ignoré |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_record(record)](#create_from_record_record_3) | Initialise une nouvelle instance de la classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'en-tête. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | L'en-tête. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'en-tête. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Initialise une nouvelle instance de la classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | L'en-tête. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

Initialise une nouvelle instance de la classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | L'enregistrement. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


