---
title: "Classe EmfLogBrushEx"
type: docs
weight: 120
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Initialise une nouvelle instance de la classe EmfLogBrushEx |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Obtient ou définit un objet WMF ColorRef de 32 bits ([MS-WMF] section 2.2.2.8) qui spécifie une<br/>            couleur. L’interprétation de ce champ dépend de la valeur de BrushStyle, comme expliqué dans le<br/>            tableau suivant. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Obtient ou définit un champ non signé de 32 bits qui contient les données de hachure du pinceau. Son <br/>            interprétation dépend de la valeur de BrushStyle, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Obtient ou définit un entier non signé de 32 bits qui spécifie le style du pinceau. La valeur MUST <br/>            être une énumération de l’énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). Les valeurs de style <br/>            prises en charge dans cette structure sont listées plus loin dans cette section. Le style BS_NULL <br/>            SHOULD être utilisé pour spécifier un pinceau qui n’a aucun effet. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Initialise une nouvelle instance de la classe EmfLogBrushEx

