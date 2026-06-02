---
title: "EmfPlusFillClosedCurve-klass"
type: docs
weight: 230
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Initierar en ny instans av klassen [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger penselidentifieraren<br/>            Ett 32‑bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S‑biten i Flags‑fältet. Denna pensel används för att fylla insidan <br/>            av den slutna kardinalsplinen. |
| compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) är komprimerad.<br/>            Denna bit indikerar om PointData‑fältet specificerar komprimerad data.<br/>            Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars <br/>            heltalskoordinater. Om avmarkerat, specificerar PointData absoluta positioner i <br/>            koordinatrymden med 32‑bitars flyttalskoordinater.<br/>            ----------------------<br/>            En "winding"‑fyllningsoperation fyller områden enligt regeln för "even-odd parity". <br/>            Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en <br/>            sluten kurva på följande sätt: Rita en linje från testpunkten till en punkt som ligger långt <br/>            från kurvan. Om den linjen korsar kurvan ett udda antal gånger är testpunkten innanför kurvan; annars är testpunkten utanför kurvan.<br/>            ---------------------<br/>            En "alternate"‑fyllningsoperation fyller områden enligt "non-zero"‑regeln.<br/>            Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför <br/>            en sluten kurva på följande sätt: Rita en linje från en testpunkt till en punkt som är <br/>            långt från kurvan. Räkna antalet gånger kurvan korsar testlinjen från vänster till höger, och räkna antalet gånger kurvan korsar <br/>            testlinjen från höger till vänster. Om de två siffrorna är lika är testpunkten <br/>            utanför kurvan; annars är testpunkten innanför kurvan. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/>            Om satt, specificerar BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1).<br/>            Om rensad, innehåller BrushId indexet för ett EmfPlusBrush-objekt <br/>            (avsnitt 2.2.1.1) i EMF+ objekt-tabellen. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger punktdata<br/>            En array av Count‑punkter som specificerar ändpunkterna för linjerna som definierar splinen. <br/>            I en sluten kardinalspline fortsätter kurvan genom den sista punkten i PointData-<br/>            arrayen och ansluter till den första punkten i arrayen. |
| relative | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) är relativ.<br/>            Denna bit indikerar om PointData‑fältet specificerar relativa eller absoluta positioner.<br/>            Om satt, specificerar varje element i PointData en plats i koordinatrymden som är<br/>            relativ till platsen som anges av föregående element i arrayen. För det första <br/>            elementet i PointData antas en föregående plats vid koordinaterna (0,0). <br/>            Om avmarkerat, specificerar PointData absoluta positioner enligt C‑flaggan.<br/>            Obs! Om denna flagga är satt är C‑flaggan (ovan) odefinierad och MÅSTE ignoreras. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| spänning | float | r/w | Hämtar eller anger spänningen<br/>            Ett 32‑bitars flyttal som specificerar hur kraftigt splinen böjs när den passerar <br/>            genom punkterna. Ett värde på 0.0 betyder att splinen är en sekvens av raka <br/>            linjer. När värdet ökar blir kurvan mer rundad. För mer information, <br/>            se [SPLINE77] och [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |
| winding | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) är winding.<br/>            Denna bit indikerar hur fyllningsoperationen ska utföras.<br/>            Om satt, är fyllningen en "winding"‑fyllning. Om avmarkerat, är fyllningen en "alternate"‑fyllning. |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Initierar en ny instans av klassen [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

