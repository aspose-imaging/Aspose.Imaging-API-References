---
title: "EmfPlusBitmapData klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | Initierar en ny instans av EmfPlusBitmapData‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Hämtar eller anger palettfärgerna <br/>            Colors (variabel): Ett valfritt [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/)‑objekt (avsnitt 2.2.2.28), som specificerar paletten<br/>            av färger som används i pixeldata. Detta fält MUST vara närvarande om I‑flaggan är satt i PixelFormat‑fältet i<br/>            [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/)‑objektet. |
| pixel_data | System.Byte | r/w | Hämtar eller anger pixeldata <br/>            PixelData (variabel): En byte‑array som specificerar pixeldata. Storleken och formatet på dessa data kan<br/>            beräknas från fält i EmfPlusBitmap‑objektet, inklusive pixelformatet från<br/>            [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/)‑enumerationen (avsnitt 2.1.1.25). |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

Initierar en ny instans av EmfPlusBitmapData‑klassen

