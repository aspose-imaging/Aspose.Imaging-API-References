---
title: "Classe EmfLogPenEx"
type: docs
weight: 190
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Initialise une nouvelle instance de la classe EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8). L'interprétation de ce<br/>            champ dépend de la valeur BrushStyle, comme indiqué dans le tableau plus loin dans cette section. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Obtient ou définit le motif dib du pinceau. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Obtient ou définit le motif hachuré du pinceau. La définition de ce champ dépend de la valeur <br/>            BrushStyle, comme indiqué dans le tableau plus loin dans cette section. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie un style de pinceau pour le crayon à partir de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). <br/>            Si le type de crayon dans le champ PenStyle est PS_GEOMETRIC, cette valeur DOIT être soit <br/>            BS_SOLID soit BS_HATCHED. La valeur de ce champ peut être BS_NULL, mais uniquement si le <br/>            style de ligne spécifié dans PenStyle est PS_NULL. Le style BS_NULL DOIT être utilisé <br/>            pour spécifier un pinceau qui n'a aucun effet. |
| num_style_entities | int | r | Obtient le nombre d'éléments dans le tableau spécifié dans le champ StyleEntry. <br/>            Cette valeur DOIT être zéro si PenStyle ne spécifie pas PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Obtient ou définit le style du crayon |
| style_entry | int[] | r/w | Obtient ou définit un tableau optionnel d'entiers non signés de 32 bits qui définit les longueurs des <br/>            tirets et des espaces dans la ligne tracée par ce crayon, lorsque la valeur de PenStyle <br/>            est le style de ligne PS_USERSTYLE pour le crayon. Le tableau contient un nombre d' <br/>            entrées spécifiées par NumStyleEntries, mais il est utilisé comme s'il se répétait indéfiniment <br/>            La première entrée du tableau spécifie la longueur du premier tiret. La deuxième <br/>            entrée spécifie la longueur du premier espace. Par la suite, les longueurs des tirets et des espaces alternent.<br/>            Si le type de crayon dans le champ PenStyle est PS_GEOMETRIC, les longueurs sont spécifiées en <br/>            unités logiques ; sinon, les longueurs sont spécifiées en unités de dispositif. |
| width | int | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie la largeur de la ligne tracée par le crayon.<br/>            Si le type de crayon dans le champ PenStyle est PS_GEOMETRIC, cette valeur est la largeur en<br/>            unités logiques ; sinon, la largeur est spécifiée en unités de dispositif. <br/>            Si le type de crayon dans le champ PenStyle est PS_COSMETIC, cette valeur DOIT être 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Initialise une nouvelle instance de la classe EmfLogPenEx

