---
title: "EmfLogBrushEx-klass"
type: docs
weight: 120
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Initierar en ny instans av EmfLogBrushEx-klass |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Hämtar eller anger ett 32-bitars WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar en<br/>            färg. Tolkningen av detta fält beror på värdet av BrushStyle, enligt förklaringen i<br/>            följande tabell. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Hämtar eller anger ett 32-bitars osignerat fält som innehåller penseldragningsdata. Dess <br/>            tolkning beror på värdet av BrushStyle, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar penselstilen. Värdet MÅSTE <br/>            vara en uppräkning från WMF BrushStyle-uppräkning ([MS-WMF] avsnitt 2.1.1.4). Stil-<br/>            värdena som stöds i denna struktur listas senare i detta avsnitt. BS_NULL-stilen <br/>            BÖR användas för att specificera en pensel som inte har någon effekt. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Initierar en ny instans av EmfLogBrushEx-klass

