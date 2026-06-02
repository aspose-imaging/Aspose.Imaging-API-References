---
title: "EmfStretchDiBits Class"
type: docs
weight: 1410
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | Initialise une nouvelle instance de la classe [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie une opération raster <br/>            code. Ces codes définissent comment les données de couleur du rectangle source doivent être combinées avec <br/>            les données de couleur du rectangle destination et éventuellement un motif de pinceau, pour obtenir la couleur finale. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le <br/>            rectangle de délimitation de destination en unités de dispositif. |
| cx_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| cx_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur en pixels du rectangle source. |
| cy_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| cy_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur en pixels du rectangle source. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas obligé d'être <br/>            contigu avec la partie fixe de l'enregistrement EMR_STRETCHDIBITS. En conséquence, les champs de <br/>            ce tampon qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la <br/>            table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9). |
| x_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle de destination. |
| x_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x en pixels du coin supérieur gauche <br/>            du rectangle source. |
| y_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle de destination. |
| y_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y en pixels du coin supérieur gauche <br/>            du rectangle source. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

Initialise une nouvelle instance de la classe [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/).

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


