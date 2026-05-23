---
title: "EmfLogPenEx-klass"
type: docs
weight: 190
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Initierar en ny instans av klassen EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8). Tolkningen av detta<br/>            fält beror på BrushStyle‑värdet, enligt tabellen längre ner i detta avsnitt. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger borstens dib-mönster. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Hämtar eller anger borstens ryggmönster. Definitionen av detta fält beror på <br/>            BrushStyle‑värdet, enligt tabellen längre ner i detta avsnitt. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar en borststil för pennan från<br/>            WMF BrushStyle‑enumerationen ([MS-WMF] avsnitt 2.1.1.4). <br/>            Om penntypen i PenStyle‑fältet är PS_GEOMETRIC, måste detta värde vara antingen <br/>            BS_SOLID eller BS_HATCHED. Värdet i detta fält kan vara BS_NULL, men endast om <br/>            linjestilen som anges i PenStyle är PS_NULL. BS_NULL‑stilen BÖR användas <br/>            för att specificera en borste som inte har någon effekt. |
| num_style_entities | int | r | Hämtar antalet element i arrayen som specificeras i StyleEntry‑fältet. <br/>            Detta värde BÖR vara noll om PenStyle inte specificerar PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Hämtar eller anger pennstilen |
| style_entry | int[] | r/w | Hämtar eller anger en valfri array av 32-bitars osignerade heltal som definierar längderna på <br/>            streck och mellanrum i linjen som ritas av denna penna, när värdet i PenStyle <br/>            är PS_USERSTYLE‑linjestil för pennan. Arrayen innehåller ett antal <br/>            poster som specificeras av NumStyleEntries, men den används som om den upprepas oändligt <br/>            Den första posten i arrayen anger längden på det första strecket. Den andra <br/>            posten anger längden på det första mellanrummet. Därefter alternerar längderna på streck och mellanrum.<br/>            Om penntypen i PenStyle‑fältet är PS_GEOMETRIC, anges längderna i <br/>            logiska enheter; annars anges de i enheter för enheten. |
| width | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar bredden på linjen som ritas av pennan.<br/>            Om penntypen i PenStyle‑fältet är PS_GEOMETRIC, är detta värde bredden i<br/>            logiska enheter; annars anges bredden i enheter för enheten. <br/>            Om penntypen i PenStyle‑fältet är PS_COSMETIC, MÅSTE detta värde vara 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Initierar en ny instans av klassen EmfLogPenEx

