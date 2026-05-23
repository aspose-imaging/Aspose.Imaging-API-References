---
title: "EmfPlusTextureBrushData-klass"
type: docs
weight: 680
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Initierar en ny instans av klassen EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. <br/>            Detta värde MÅSTE bestå av BrushData-flaggor (avsnitt 2.1.2.1). <br/>            Följande flaggor är relevanta för en texture brush<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Hämtar eller anger ett valfritt EmfPlusTextureBrushOptionalData-objekt (avsnitt 2.2.2.46) som <br/>            specificerar ytterligare data för texture brush. Det specifika innehållet i <br/>            detta fält bestäms av värdet i BrushDataFlags-fältet |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑uppräkningen (avsnitt 2.1.1.34) <br/>            som specificerar hur texturbilden ska upprepas över en form, när <br/>            bilden är mindre än det område som fylls. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Initierar en ny instans av klassen EmfPlusTextureBrushData

