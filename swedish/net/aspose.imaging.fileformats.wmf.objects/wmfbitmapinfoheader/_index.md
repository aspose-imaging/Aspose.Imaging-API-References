---
title: WmfBitmapInfoHeader
second_title: Aspose.Imaging för .NET API-referens
description: BitmapInfoHeader-objektet innehåller information om dimensionerna och färgformatet för en enhetsoberoende bitmapp DIB.
type: docs
weight: 8470
url: /sv/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

BitmapInfoHeader-objektet innehåller information om dimensionerna och färgformatet för en enhetsoberoende bitmapp (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som definierar formatet för varje pixel och det maximala antalet färger i DIB. Detta värde MÅSTE finnas i[`BitCount`](../wmfbitmapbaseheader/bitcount) Uppräkning (avsnitt 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa DIB. Om detta värde är noll krävs alla färgindex |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger antalet index i färgtabellen som används av DIB, som följer: Om detta värde är noll, använder DIB det maximala antalet färger som motsvarar BitCount-värdet. Om detta värde inte är noll och BitCount-värdet är mindre än 16, anger detta värde antalet färger som används av DIB. Om detta värde inte är noll och BitCount-värdet är 16 eller högre, anger detta värde storleken på färgen table används för att optimera prestanda för systempaletten. Obs! Om detta värde inte är noll och större än den maximala möjliga storleken på färgtabellen baserat på värdet BitCount SKA den maximala färgtabellstorleken antas. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. Detta värde MÅSTE finnas i Compression Enumeration (avsnitt 2.1.1.7). Detta värde FÅR INTE specificera ett komprimerat format om DIB är en top-down bitmapp, vilket indikeras av Height value. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar storleken på detta objekt, i bytes. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Hämtar eller ställer in 32-bitars heltal med tecken som definierar höjden på DIB, i pixlar. Detta värde FÅR INTE vara noll. Om detta värde är positivt är DIB en bitmapp nedifrån och upp och dess ursprung är det nedre vänstra hörnet. Om detta värde är negativt är DIB en bitmapp uppifrån och ner, och dess ursprung är det övre vänstra hörnet. Top-down bitmaps stöder inte komprimering. Det här fältet SKA ange höjden på den dekomprimerade bildfilen, om komprimeringsvärdet anger JPEG- eller PNG -format. |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som definierar storleken, i byte, av bilden. Om komprimeringsvärdet är BI_RGB SKA detta värde vara noll och MÅSTE ignoreras. Om komprimeringsvärdet är BI_PEG eller BI_PNG detta värde MÅSTE ange storleken på JPEG- eller PNG-bildbufferten, respektive. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som definierar antalet planes för målenheten. Detta värde MÅSTE vara 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som definierar bredden på DIB, i pixlar. Detta värde MÅSTE vara positivt. Det här fältet SKA ange bredden på den dekomprimerade bildfilen, om komprimeringsvärdet anger JPEG- eller PNG -format. |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar per meter, för target -enheten för DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Hämtar eller ställer in ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar per meter, för target -enheten för DIB |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | Strukturens storlek |

### Se även

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* namnutrymme [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
