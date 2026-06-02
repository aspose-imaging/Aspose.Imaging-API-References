---
title: "EmfPlgBlt Classe"
type: docs
weight: 750
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Initialise une nouvelle instance de la classe [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Obtient ou définit un tableau de trois objets WMF PointL ([MS-WMF] section 2.2.2.15) qui<br/>spécifie trois coins d'une zone de destination en parallélogramme pour le transfert de bloc.<br/>Le coin supérieur gauche du rectangle source est mappé au premier point de ce tableau, le<br/>coin supérieur droit au deuxième point, et le coin inférieur gauche au troisième point. Le coin inférieur droit du rectangle source est mappé au quatrième point implicite du<br/>parallélogramme, qui est calculé à partir des trois premiers points (A, B et C) en les traitant comme<br/>des vecteurs.<br/>D = B + C A |
| bk_src_argb_32_color | int | r/w | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8) qui spécifie la<br/>couleur d'arrière-plan du bitmap source. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtient ou définit un objet WMF RectL ([MS-WMF] section 2.2.2.19) qui définit le<br/>rectangle englobant, en unités de dispositif, pour la sortie vers la destination. |
| cx_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur logique du rectangle source. |
| cy_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur logique du rectangle source. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap de masque, qui ne sont pas <br/>            requis d'être contigus avec la partie fixe de l'enregistrement EMR_PLGBLT ou entre eux. <br/>            En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
| size | int | r/w | Obtient ou définit la taille de l'enregistrement |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit un tampon contenant le bitmap source, qui ne sont pas <br/>            requis d'être contigus avec la partie fixe de l'enregistrement EMR_PLGBLT ou entre eux. <br/>            En conséquence, les champs de ce tampon portant le libellé "UndefinedSpace" sont optionnels et DOIVENT être ignorés. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Obtient ou définit le type. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la <br/>            table de couleurs de l'en-tête du bitmap de masque. Cette valeur DOIT appartenir à l'énumération DIBColors. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie comment interpréter les valeurs dans la <br/>            table de couleurs de l'en-tête du bitmap source. Cette valeur DOIT appartenir à l'énumération DIBColors. |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtient ou définit un objet XForm (section 2.2.28) qui spécifie une transformation de l'espace mondial vers l'espace page à appliquer au bitmap source. |
| x_mask | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche du bitmap de masque. |
| x_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée x logique du coin supérieur gauche <br/>            du rectangle source. |
| y_mask | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche du bitmap de masque. |
| y_src | int | r/w | Obtient ou définit un entier signé de 32 bits qui spécifie la coordonnée y logique du coin supérieur gauche <br/>            du rectangle source. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initialise une nouvelle instance de la classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Initialise une nouvelle instance de la classe [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

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


