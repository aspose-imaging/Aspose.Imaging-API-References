---
title: "EmfPlusBitmap-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Initierar en ny instans av EmfPlusBitmap-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Hämtar eller anger bitmapdata<br/>            BitmapData (variabel): Variabelt data som definierar bitmapdataobjektet som anges i Type‑fältet. <br/>            innehållet och formatet på datan kan vara olika för varje bitmap-typ. |
| height | int | r/w | Hämtar eller anger bitmaphöjd<br/>            Height (4 byte): Ett 32-bitars signerat heltal som specificerar höjden i pixlar för det område som bitmapen upptar.<br/>            Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Hämtar eller anger pixelformat<br/>            PixelFormat (4 byte): Ett 32-bitars osignerat heltal som specificerar formatet på pixlarna som utgör bitmap‑bilden.<br/>            De stödjade pixelformaten anges i [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/)-enumerationen (avsnitt 2.1.1.25).<br/>            Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras. |
| stride | int | r/w | Hämtar eller anger bildens radsteg (stride)<br/>            Stride (4 byte): Ett 32-bitars signerat heltal som specificerar byteavståndet mellan början av en scan‑rad och<br/>            nästa. Detta värde är antalet byte per pixel, vilket anges i PixelFormat‑fältet, multiplicerat med<br/>            bredden i pixlar, som anges i Width‑fältet. Värdet i detta fält MÅSTE vara en multipel av fyra.<br/>            Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Hämtar eller anger bildens typ<br/>            Type (4 byte): Ett 32-bitars osignerat heltal som specificerar datatypen i BitmapData‑fältet. Detta värde MÅSTE<br/>            vara definierat i [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/)-enumerationen (avsnitt 2.1.1.2). |
| width | int | r/w | Hämtar eller anger bildens bredd<br/>            Width (4 byte): Ett 32-bitars signerat heltal som specificerar bredden i pixlar för det område som bitmapen upptar.<br/>            Om bilden är komprimerad, enligt Type‑fältet, är detta värde odefinierat och MÅSTE ignoreras. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Initierar en ny instans av EmfPlusBitmap-klassen

