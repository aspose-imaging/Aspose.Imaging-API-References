---
title: "EmfCreateMonoBrush Classe"
type: docs
weight: 300
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

**Summary:** The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateMonoBrush(source)](#EmfCreateMonoBrush_source_1) | Initialise une nouvelle instance de la classe [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant un DIB empaqueté sous la forme d'un objet WMF<br/>            DeviceIndependentBitmap ([MS-WMF] section 2.2.2.9). Il n'est pas nécessaire qu'il soit<br/>            contigu avec la partie fixe de l'enregistrement EMR_CREATEDIBPATTERNBRUSHPT. |
| ih_brush | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie l’index de l’objet pinceau à motif monochrome<br/>            dans la table d’objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la table de couleur<br/>            du header DIB. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateMonoBrush(source) {#EmfCreateMonoBrush_source_1}


```
 EmfCreateMonoBrush(source) 
```

Initialise une nouvelle instance de la classe [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/).

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


