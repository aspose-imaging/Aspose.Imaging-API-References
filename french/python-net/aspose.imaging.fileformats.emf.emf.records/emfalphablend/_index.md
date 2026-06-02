---
title: "EmfAlphaBlend Classe"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Initialise une nouvelle instance de la classe [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la<br/>            couleur d'arrière-plan du bitmap source. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Obtient ou définit une structure qui spécifie les opérations de fusion pour les bitmaps source et <br/>            destination. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le <br/>            rectangle de délimitation de destination en unités de dispositif. |
| cx_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle de destination <br/>            . Cette valeur DOIT être supérieure à zéro. |
| cx_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. <br/>            Cette valeur DOIT être supérieure à zéro. |
| cy_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle de destination <br/>            . Cette valeur DOIT être supérieure à zéro. |
| cy_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source <br/>            . Cette valeur DOIT être supérieure à zéro. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap source, qui n'est pas obligé d'être <br/>            contigu avec la partie fixe de l'enregistrement EMR_ALPHABLEND. En conséquence, les champs de ce <br/>            tampon qui sont étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la <br/>            table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors (section 2.1.9). |
| x_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle de destination. |
| x_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle source. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| y_dest | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle de destination. |
| y_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle source. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Initialise une nouvelle instance de la classe [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/).

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


