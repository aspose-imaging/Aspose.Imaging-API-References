---
title: EmfSetPolyFillMode
second_title: Aspose.Imaging för .NET API-referens
description: EMR_SETPOLYFILLMODE-posten definierar polygonfyllningsläge.
type: docs
weight: 4460
url: /sv/net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

EMR_SETPOLYFILLMODE-posten definierar polygonfyllningsläge.

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor)() | Initierar en ny instans av[`EmfSetPolyFillMode`](../emfsetpolyfillmode) class. |
| [EmfSetPolyFillMode](emfsetpolyfillmode#constructor_1)(EmfRecord) | Initierar en ny instans av[`EmfSetPolyFillMode`](../emfsetpolyfillmode) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode) { get; set; } | Hämtar eller ställer in ett 32-bitars heltal utan tecken som anger polygonfyllningsläget och MÅSTE vara i uppräkningen PolygonFillMode (avsnitt 2.1.27). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Hämtar eller ställer in storleken på posten |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Hämtar eller ställer in typen. |

### Anmärkningar

I allmänhet skiljer sig lägena endast i de fall där en komplex, överlappande polygon MÅSTE fyllas; for exempel, en femsidig polygon som bildar en femuddig stjärna med en femhörning i mitten. I sådana fall SKA ALTERNAT-läget fylla varannan innesluten region inom polygonen (punkterna för stjärnan), men WINDING-läget SKA fylla alla områden (stjärnans och femhörningens punkter). När fyllningsläget är ALTERNATIV, område mellan udda och jämna polygon sidor på varje skanningslinje SKA fyllas i. Det vill säga området mellan den första och andra sidan SKA fyllas, och mellan den tredje och fjärde sidan, och så vidare. När fyllningsläget är WINDING, SKA alla regioner som har ett lindningsvärde som inte är noll fyllas. Lindningen värde är antalet gånger en penna som används för att rita polygonen skulle gå runt området . Riktningen för varje kant av polygonen är signifikant.

### Se även

* class [EmfStateRecordType](../emfstaterecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
