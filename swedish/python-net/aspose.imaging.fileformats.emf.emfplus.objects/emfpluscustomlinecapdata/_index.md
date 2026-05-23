---
title: "EmfPlusCustomLineCapData klass"
type: docs
weight: 270
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Initierar en ny instans av klassen EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet från LineCap‑enumerationen (avsnitt 2.1.1.18) <br/>            som den anpassade linjekappen är baserad på. |
| base_inset | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar avståndet mellan början <br/>            av linjekappen och slutet av linjen. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger ett EmfPlusPointF-objekt som för närvarande inte används. Det MÅSTE sättas till {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Hämtar eller anger ett valfritt EmfPlusCustomLineCapOptionalData-objekt (avsnitt 2.2.2.14)<br/>             som specificerar ytterligare data för den anpassade grafiska linjekappen. D<br/>            e specifika innehållet i detta fält bestäms <br/>            av värdet i fältet CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar vilken <br/>            linjekapp som ska användas i slutet av den linje som ska ritas. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger ett EmfPlusPointF-objekt som för närvarande inte används. Det MÅSTE sättas till {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineJoin‑enumerationen <br/>            (avsnitt 2.1.1.19), som specificerar hur två linjer som ritas med<br/>             samma penna och vars ändar möts ska förenas. Vid skärningspunkten mellan de två linjeändarna, <br/>            gör en linjeslutning anslutningen mer kontinuerlig. |
| stroke_miter_limit | float | r/w | Hämtar eller anger ett 32-bitars flyttal som innehåller gränsen för tjockleken<br/>             på föreningen i ett snedskuret hörn genom att sätta det maximala tillåtna förhållandet<br/>             mellan snedskärningens längd och linjebredden. |
| stroke_start_cap | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar värdet i LineCap‑enumerationen som indikerar <br/>            linjekappen som används i början av den linje som ska ritas. |
| width_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar mängden med vilken man<br/>             skalar den anpassade linjekappen i förhållande till bredden på EmfPlusPen-<br/>            objektet (avsnitt 2.2.1.7) som används för att rita linjerna. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Initierar en ny instans av klassen EmfPlusCustomLineCapData

