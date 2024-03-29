---
title: EmfPlusPathPointFlags
second_title: Aspose.Imaging för .NET API-referens
description: Ett 32-bitars osignerat heltal som anger hur man tolkar punkterna och associerade punkttyper som definieras av detta objekt. C 1 bit Om angivet anger PathPoints-matrisen absoluta platser i koordinatutrymmet med 16-bitars heltal coordinates. Om den är ren anger PathPoints-matrisen absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater. Obs Om P-flaggan nedan är inställd KAN denna flagga vara ren och MÅSTE ignoreras. R  1 bit Om inställt specificeras punkttyperna i PathPointTypes-matrisen av EmfPlusPlusPathPointTypeRle-objekt avsnitt 2.2.2.32 som använder run-length encoding RLE-komprimering och/eller EmfPlusPathPointType-objekt sektion 2.32.. Se MS-WMF avsnitt 3.1.6 för mer information om RLE-komprimering. Om den är ren specificeras punkttyperna i PathPointTypes-matrisen av EmfPlusPathPointType-objekt. P 1 bit Om inställt varje element i PathPoints-matrisen anger en plats i koordinatutrymmet som är relativt platsen specificerad av det föregående elementet i arrayen. I fallet med det första elementet i PathPoints antas en tidigare plats vid koordinaterna 00. Om den är ren anger varje element i PathPoints-matrisen en absolut plats.
type: docs
weight: 4960
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

Ett 32-bitars osignerat heltal som anger hur man tolkar punkterna och associerade punkttyper som definieras av detta objekt. C (1 bit): Om angivet, anger PathPoints-matrisen absoluta platser i koordinatutrymmet med 16-bitars heltal coordinates. Om den är ren, anger PathPoints-matrisen absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater. Obs Om P-flaggan (nedan) är inställd, KAN denna flagga vara ren och MÅSTE ignoreras. R ( 1 bit): Om inställt, specificeras punkttyperna i PathPointTypes-matrisen av EmfPlusPlusPathPointTypeRle-objekt (avsnitt 2.2.2.32), som använder run-length encoding (RLE)-komprimering och/eller EmfPlusPathPointType-objekt (sektion 2.32.). Se [MS-WMF] avsnitt 3.1.6 för mer information om RLE-komprimering. Om den är ren, specificeras punkttyperna i PathPointTypes-matrisen av EmfPlusPathPointType-objekt. P (1 bit): Om inställt, varje element i PathPoints-matrisen anger en plats i koordinatutrymmet som är relativt platsen specificerad av det föregående elementet i arrayen. I fallet med det första elementet i PathPoints antas en tidigare plats vid koordinaterna (0,0). Om den är ren, anger varje element i PathPoints-matrisen en absolut plats.

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| C | `4000` | C-flaggan |
| R | `1000` | R-flaggan |
| P | `800` | P-flaggan |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
