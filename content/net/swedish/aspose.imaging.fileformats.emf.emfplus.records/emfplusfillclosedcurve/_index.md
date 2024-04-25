---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusFillClosedCurve-posten anger fyllning av det inre av en stängd kardinalspline
type: docs
weight: 6060
url: /sv/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

EmfPlusFillClosedCurve-posten anger fyllning av det inre av en stängd kardinalspline

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Hämtar eller ställer in penselidentifieraren Ett 32-bitars osignerat heltal som specificerar EmfPlusBrush, vars innehåll bestäms av S-biten i Flags-fältet. Denna borste används för att fylla det inre av den stängda kardinalspline. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)är komprimerad. Denna bit indikerar om PointData-fältet specificerar komprimerad data. Om den är inställd, specificerar PointData absoluta platser i koordinatutrymmet med 16-bitars heltalskoordinater. Om den är ren, specificerar PointData absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater. ---------------------- En "lindande" fyllning operation fyller områden enligt regeln "jämn-udda paritet". Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en stängd kurva enligt följande: Rita en linje från testpunkten till en punkt som är avlägsen från kurvan. Om den linjen korsar kurvan ett udda antal gånger, är testpunkten innanför kurvan; annars är testpunkten utanför kurvan. --------------------- En "alternativ" fyllningsoperation fyller områden enligt regeln "icke-noll" . Enligt denna regel kan en testpunkt bestämmas vara innanför eller utanför en sluten kurva enligt följande: Rita en linje från en testpunkt till en punkt som är avstånd från kurvan. Räkna antalet gånger kurvan korsar testlinjen från vänster till höger, och räkna antalet gånger kurvan korsar testlinjen från höger till vänster. Om dessa två siffror är lika, är testpunkten utanför kurvan; annars är testpunkten innanför kurvan. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna instans är färg. Om den är inställd, anger BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1). Om det är klart innehåller BrushId indexet för ett EmfPlusBrush-objekt 2. ) i objekttabellen EMF+. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Hämtar eller ställer in punktdata En matris med Räknepunkter som anger ändpunkterna för linjerna som definierar spline. I en sluten kardinalspline fortsätter kurvan genom den sista punkten i PointData -matrisen och ansluter till den första punkten i matrisen |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) is relative. Den här biten indikerar om PointData-fältet specificerar relativa eller absoluta platser. Om satt, specificerar varje element i PointData en plats i koordinatutrymmet som är relativt den plats som specificerats av föregående element i arrayen. I fallet för det första elementet i PointData antas en tidigare plats vid koordinaterna (0,0). Om den är ren, specificerar PointData absoluta platser enligt C-flaggan. Notera Om denna flagga är inställd är C-flaggan (ovan) odefinierad och MÅSTE ignoreras. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Hämtar eller ställer in tension Ett 32-bitars flyttalsvärde som anger hur hårt splines böjs när den passerar genom punkterna. Ett värde på 0,0 anger att spline är en sekvens av raka linjer. När värdet ökar blir kurvan mer avrundad. För mer information, se [SPLINE77] och [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)is winding. Den här biten indikerar hur fyllningsoperationen ska utföras. Om den är inställd är fyllningen en "lindande" fyllning. Om den är ren, är fyllningen en "alternativ" fyllning. |

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
