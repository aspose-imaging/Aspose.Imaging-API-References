---
title: TiffRationalType
second_title: Aspose.Imaging för .NET API-referens
description: Den rationella tiff-typen.
type: docs
weight: 7980
url: /sv/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---
## TiffRationalType class

Den rationella tiff-typen.

```csharp
public sealed class TiffRationalType : TiffCommonArrayType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TiffRationalType](tiffrationaltype#constructor)(TiffTags) | Initierar en ny instans av[`TiffRationalType`](../tiffrationaltype) class. |
| [TiffRationalType](tiffrationaltype#constructor_1)(ushort) | Initierar en ny instans av[`TiffRationalType`](../tiffrationaltype) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Hämtar den extra datastorleken i byte (om de 12 byten inte räcker för att passa taggdata). |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count) { get; } | Hämtar antalet element. |
| [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/datasize) { get; } | Hämtar den extra datastorleken i byte (om de 12 byten inte räcker för att passa taggdata). |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/elementsize) { get; } | Hämtar elementstorleken i byte. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Får tagg-id heltalsrepresentation. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Får ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Hämtar tagg-id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/tagtype) { get; } | Hämtar taggtypen. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/value) { get; set; } | Hämtar eller ställer in värdet som denna datatyp innehåller. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/values) { get; set; } | Hämtar eller ställer in värdena. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/valuescontainer) { get; } | Hämtar värdebehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som anger om den aktuella instansen föregår, följer efter eller förekommer på samma position i sorteringsordningen som det andra objektet. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Utför en djup klon av denna instans. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Returnerar enString som representerar denna instans. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/writeadditionaldata)(TiffStreamWriter) | Skriver ytterligare taggdata. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Skriver taggdata. |

### Se även

* class [TiffCommonArrayType](../tiffcommonarraytype)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->