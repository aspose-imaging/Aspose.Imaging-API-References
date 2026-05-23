---
title: "EmfPlusPenOptionalData‑klass"
type: docs
weight: 560
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Initierar en ny instans av klassen EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Hämtar eller anger valfritt EmfPlusCompoundLineData‑objekt (avsnitt 2.2.2.9) <br/>            som specificerar en array av flyttalsvärden som definierar <br/>            den sammansatta linjen för en penna, som består av parallella linjer <br/>            och mellanrum. Detta fält MÅSTE finnas om <br/>            flaggan PenDataCompoundLine är satt i fältet PenDataFlags <br/>            i objektet EmfPlusPenData. |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Hämtar eller anger valfritt EmfPlusCustomEndCapData‑objekt (avsnitt 2.2.2.11) <br/>            som definierar den anpassade ändkapsel‑formen, vilken är den form som <br/>            används i slutet av en linje ritad med denna penna. Den kan vara någon av <br/>            olika former, såsom en kvadrat, cirkel eller diamant. Detta <br/>            fält MÅSTE finnas om flaggan PenDataCustomEndCap är <br/>            satt i fältet PenDataFlags i objektet EmfPlusPenData. |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Hämtar eller anger valfritt EmfPlusCustomStartCapData‑objekt (avsnitt 2.2.2.15) <br/>            som definierar den anpassade startkapsel‑formen, vilken är den form som <br/>            används i början av en linje ritad med denna penna. Den kan vara någon <br/>            av olika former, såsom en kvadrat, cirkel eller diamant. <br/>            Detta fält MÅSTE finnas om flaggan PenDataCustomStartCap är <br/>            satt i fältet PenDataFlags i objektet EmfPlusPenData. |
| dash_offset | float | r/w | Hämtar eller anger valfritt 32‑bitars flyttalsvärde som specificerar <br/>            avståndet från början av en linje till början av <br/>            det första mellanrummet i ett streckat linjemönster. Detta fält MÅSTE finnas om flaggan PenDataDashedLineOffset är satt i <br/>            fältet PenDataFlags i objektet EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen för <br/>            båda ändarna av varje streck i en streckad linje. Detta fält MÅSTE finnas om flaggan PenDataDashedLineCap är satt i <br/>            fältet PenDataFlags i objektet EmfPlusPenData, och <br/>            värdet MÅSTE definieras i uppräkningen DashedLineCapType <br/>            (avsnitt 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Hämtar eller anger ett valfritt EmfPlusDashedLineData‑objekt (avsnitt 2.2.2.16) <br/>            som specificerar längderna på streck och mellanrum i en anpassad <br/>            streckad linje. Detta fält MÅSTE finnas om flaggan PenDataDashedLine <br/>            är satt i fältet PenDataFlags i objektet EmfPlusPenData<br/>            . |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar formen<br/>             för slutet av en linje i fältet CustomEndCapData. Detta <br/>            fält MÅSTE finnas om flaggan PenDataEndCap är satt i <br/>            fältet PenDataFlags i objektet EmfPlusPenData, och värdet <br/>            MÅSTE definieras i uppräkningen LineCapType. |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar hur man förenar<br/>             två linjer som ritas med samma penna och vars ändar möts. <br/>            Detta fält MÅSTE finnas om flaggan PenDataJoin är satt i <br/>            fältet PenDataFlags i objektet EmfPlusPenData, och <br/>            värdet MÅSTE definieras i uppräkningen LineJoinType <br/>            (avsnitt 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Hämtar eller anger ett valfritt 32‑bitars signerat heltal som specificerar stilen <br/>            som används för linjer ritade med detta penna‑objekt. Detta fält MÅSTE <br/>            finnas om flaggan PenDataLineStyle är satt i <br/>            fältet PenDataFlags i objektet EmfPlusPenData, och <br/>            värdet MÅSTE definieras i uppräkningen LineStyle <br/>            (avsnitt 2.1.1.20). |
| miter_limit | float | r/w | Hämtar eller anger ett valfritt 32-bitars flyttal som specificerar miter-<br/>            gränsen, vilket är det maximalt tillåtna förhållandet mellan miterlängd och<br/>            linjebredd. Miterlängden är avståndet från<br/>            skärningspunkten för linjens väggar på insidan av föreningen till <br/>            skärningspunkten för linjens väggar på utsidan av föreningen. <br/>            Miterlängden kan vara stor när vinkeln mellan två <br/>            linjer är liten. Detta fält MÅSTE vara närvarande om <br/>            PenDataMiterLimit-flaggan är satt i PenDataFlags-fältet <br/>            i EmfPlusPenData-objektet. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Hämtar eller anger ett valfritt 32-bitars heltal som specificerar <br/>            fördelningen av pennbredden i förhållande till <br/>            koordinaterna för den linje som ritas. Detta fält MÅSTE <br/>            vara närvarande om PenDataNonCenter-flaggan är satt i <br/>            PenDataFlags-fältet i EmfPlusPenData-objektet, och <br/>            värdet MÅSTE definieras i PenAlignment-<br/>            uppräkningen (avsnitt 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Hämtar eller anger ett valfritt 32-bitars heltal som specificerar formen för<br/>             början av en linje i CustomStartCapData-fältet. <br/>            Detta fält MÅSTE vara närvarande om PenDataStartCap-flaggan är satt <br/>            i PenDataFlags-fältet i EmfPlusPenData-objektet, och <br/>            värdet MÅSTE definieras i LineCapType-uppräkningen <br/>            (avsnitt 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett valfritt EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) <br/>            som specificerar en transformation från världsrummet till enhetens rum för <br/>            pennan. Detta fält MÅSTE vara närvarande om PenDataTransform-<br/>            flaggan är satt i PenDataFlags-fältet i EmfPlusPenData-<br/>            objektet. |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Initierar en ny instans av klassen EmfPlusPenOptionalData

