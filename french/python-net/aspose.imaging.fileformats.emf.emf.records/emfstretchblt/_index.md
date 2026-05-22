---
title: "Classe EmfStretchBlt"
type: docs
weight: 1400
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---

**Summary:** The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster<br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfStretchBlt()](#EmfStretchBlt__1) | Initialise une nouvelle instance de la classe [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
| [EmfStretchBlt(source)](#EmfStretchBlt_source_2) | Initialise une nouvelle instance de la classe [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la <br/>            couleur d'arrière-plan du bitmap source. |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le code d'opération raster <br/>            . Ce code définit comment les données de couleur du rectangle source doivent être combinées avec les <br/>            données de couleur du rectangle de destination et éventuellement un motif de brosse, pour obtenir la couleur finale. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le <br/>            rectangle de délimitation de destination en unités de dispositif. |
| cx_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination. |
| cx_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| cy_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination. |
| cy_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| dest_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit le rectangle de destination. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas obligé d'être <br/>            contigu avec la partie fixe de l'enregistrement EMR_STRETCHBLT. En conséquence, les champs de ce <br/>            tampon qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
| src_rect | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit le rectangle source. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la <br/>            table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9). |
| x_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle de destination. |
| x_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle source. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| y_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle de destination. |
| y_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle source. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchBlt() {#EmfStretchBlt__1}


```
 EmfStretchBlt() 
```

Initialise une nouvelle instance de la classe [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

### Constructor: EmfStretchBlt(source) {#EmfStretchBlt_source_2}


```
 EmfStretchBlt(source) 
```

Initialise une nouvelle instance de la classe [EmfStretchBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/).

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


