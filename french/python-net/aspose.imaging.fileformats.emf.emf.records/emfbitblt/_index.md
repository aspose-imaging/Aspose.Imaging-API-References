---
title: "EmfBitBlt Classe"
type: docs
weight: 70
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | Initialise une nouvelle instance de la classe [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le code d'opération raster <br/>            . Ce code définit comment les données de couleur du rectangle source doivent être combinées avec les <br/>            données de couleur du rectangle de destination et éventuellement un motif de brosse, pour obtenir la couleur finale. |
| bk_src_argb_32_color | int | r/w | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la<br/>            couleur d'arrière-plan du bitmap source. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le <br/>            rectangle de délimitation de destination en unités de dispositif. |
| cx_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique de la source et du <br/>            rectangle de destination. |
| cy_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique de la source et du <br/>            rectangle de destination. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas obligé d'être <br/>            contigu avec la partie fixe de l'enregistrement EMR_BITBLT. En conséquence, les champs de ce tampon <br/>            qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
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


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

Initialise une nouvelle instance de la classe [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/).

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


